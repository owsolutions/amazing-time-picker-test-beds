# Angular 2 Time Picker test beds

This repository is holding multiple version of angular and used only for `amazing-time-picker` module testing
purposes. **You should not clone or install this repository if you want use TimePicker for angular 2,4,5**

Please install dependency itself:

https://github.com/owsolutions/amazing-time-picker

or install directly from npm:
```
npm i amazing-time-picker@latest --save
```

## Reason behind this repository

`amazing-time-picker` is a Angular 2+ based module that gives you a visual time picker with advanced features.
For automated testing purposes, we test each pull request on multiple version of angular to make sure that the module is not gonna break on different version of angular.

In our CI, we will clone this library and install latest commit on them. Projects inside this repository are built
using angular-cli for version of 4 and 5. For Angular 2, we use a different boilerplate.

