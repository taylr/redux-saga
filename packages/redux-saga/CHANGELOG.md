# redux-saga

## 1.1.4
### Patch Changes

- 9d21649: Added warnings when using `take(channelOrPattern)` incorrectly with more than one parameter. It helps to surface problem with `take(ACTION_A, ACTION_B)` being used instead of `take([ACTION_A, ACTION_B])`.

- Updated dependencies [9d21649]
  - @redux-saga/core@1.1.4
