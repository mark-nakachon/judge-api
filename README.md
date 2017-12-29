# JUDGE API SERVER
[![CircleCI](https://img.shields.io/circleci/project/github/coding-blocks/judge-api.svg)](https://circleci.com/gh/coding-blocks/judge-api)
[![Travis](https://img.shields.io/travis/coding-blocks/judge-api.svg?style=flat-square)](https://travis-ci.org/coding-blocks/judge-api)
[![Codecov](https://img.shields.io/codecov/c/github/coding-blocks/judge-api.svg)](https://codecov.io/gh/coding-blocks/judge-api)

## Testing

To run mocha-based tests
```shell
npm run test
```

To get coverage report
```shell
npm run cover
```


### NOTES
If using a fresh db, seed the languages before testing

```shell
npm run build
npm run seedlangs
```