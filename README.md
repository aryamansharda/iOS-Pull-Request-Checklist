# iOS-PR-Checklist



- [ ] [ ] Am I duplicating existing code?
- [ ]   Did I test for memory leaks? Did I make everything `weak` that should be?
- [ ]   Did I test night mode support or remember to disable it?
- [ ]   Did I test multiple screen sizes and orientations?
- [ ]   Did I test on the lowest iOS version we support?
- [ ]   Did I test what happens if the user declines / limits permission access (location, camera roll, contacts, etc)?
- [ ]   Did I test for accessibility compatibility?
- [ ]   Am I introducing any long running operations on the main thread?
- [ ]   Did you specify the correct access level for any new entity you introduced?
- [ ]   Am I using any "magic numbers"? Should I add them to our Constants?
- [ ]   Am I following the teams coding conventions throughout my changes?
- [ ]   _Did I test with `Double Length Pseudolanguage` to ensure that the view responds to text that wraps / more verbose languages?_
- [ ]   _Did I test other languages we support to ensure there's no missing translations?_
- [ ]   Is everything behind a feature flag that should be?
- [ ]   Am I force unwrapping anything?
- [ ]   Did I resolve any ambiguous constraints / handle any runtime breaking constraint issues?
- [ ]   Am I introducing any unnecessary import statements?
- [ ]   If you added a `default` case to a `switch`, are you absolutely sure that's the ideal solution?
- [ ]   Did I document everything that I needed to?
- [ ]   Did I test a poor or offline WiFi connection?
- [ ]   Did I receive design and product approval?
- [ ]   Did I test different locales and languages? Did the currency, time, and date formatting work as expected?
- [ ]   Did I remove any extraneous `self` references? [Swift only]
- [ ]   Could any of my new code be replaced by native functions or existing helper functions?
- [ ]   Did I chose appropriate names for my classes, enums, structs, methods, and variables?
- [ ]   Am I handling and logging all errors correctly?
- [ ]   Does linting pass?
- [ ]   Are there tests? Should there be?
- [ ]   Does my PR include screenshots and instructions on how to test these changes?
- [ ]   Am I introducing any new warnings into the Xcode project?
- [ ]   Do the existing tests (unit & UI) pass?
- [ ]   Did I remove any commented out code?
- [ ]   Did I pull in `master` and resolve any merge conflicts before opening a pull request?
- [ ]   Did I remove all `TODO`, `@hack`, and placeholder code?
- [ ]   Did I remove all of the `print` statements I was using? Am I doing any unnecessary logging?
