# DaysUntilChristmasSpecification

## Requirements

### Must have

- The application must show the time until Christmas, and include the following information:
  - Number of days
  - Number of hours
  - Number of minutes
  - Number of seconds
- Be a desktop application

### Should have

- The time until Christmas should update dynamically without user interaction
- The process should exit cleanly when the native desktop application close button (`X`) is pressed
  - The process should exit with exit code 0
  - The process should not leave orphaned processes

### Could have

- The internal window view should be `123px` by `149px`
- Have text in the following form (where `D`, `H`, `M` and `S` are integers):

  ```
  D days
  H hours
  M minutes
  S seconds
  until Xmas!
  ```

### Would be nice

- It would be nice for the application to be executable without the need of a terminal or startup script
- It would be nice for the application to be small in file size. Applications will be awarded the following:
  - 🥇: < 400KB
  - 🥈: < 3MB
  - 🥉: <= 10MB
  - 💩: > 10MB
- It would be nice for the application to have a small running memory footprint. Applications will be awarded the following:
  - For Windows:
    - 🥇: < 5MB
    - 🥈: < 20MB
    - 🥉: < 40MB
    - 💩: <= 75MB
    - 🗑️: > 75MB
  - For MacOS:
    - 🥇: < 20MB
    - 🥈: < 40MB
    - 🥉: <= 75MB
    - 💩🗑️: > 75MB

## History

22nd December 2012

![A small Windows desktop application that says "2 days 4 hours 0 minutes 0 seconds until Xmas!"](https://github.com/Days-Until-Christmas/DaysUntilChristmasSpecification/assets/4613171/8c07f9a4-4bde-4d5c-9c9e-bdf1b0d50477)
