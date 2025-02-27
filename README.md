# Project Title

Simple library to get today day.

## Description

When you dont know what day today, use this library.

### Dependencies

- Node.js 4.9.1+

### Installing

- npm i today-day

### Executing program

- How to run the program

```
const todayDay = require('today-day')

//Friday
todayDay.today();

//Monday
todayDay.random();

//Tuesday
todayDay.addDays(4);

//Wednesday
todayDay.addDays(-29);


//set language to hebrew
todayDay.locale('he_IL');

//שישי
todayDay.today();

//["en_US", "fr_FR", "he_IL"]
todayDay.getSupportedLanguages();

```

- How to run tests
```
npm run test
```

## i18n
- English (en_US)
- Hebrew (he_IL)
- French (fr_FR)

## Version History

- 1.1.2
  - Added random function
  - Added addDays function
- 1.1.1
  - Changed function name setLanguages to locale
  - Removed todayUpperCase
  - Removed todayLowerCase
- 1.1.0
  - Added Jest library for tests.
- 1.0.9
  - Added support in Hebrew language.
  - Added support in French language.
  - Added function to set language.
  - Added function to get supported languages.
