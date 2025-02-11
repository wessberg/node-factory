## [4.0.4](https://github.com/wessberg/compatfactory/compare/v4.0.3...v4.0.4) (2024-10-31)

## [4.0.3](https://github.com/wessberg/compatfactory/compare/v4.0.2...v4.0.3) (2024-10-31)

### Bug Fixes

- bugs related to createImportDeclaration on older TypeScript versions ([8ef960e](https://github.com/wessberg/compatfactory/commit/8ef960e62b25b3c5870251551e13c0efbab8dec1))

## [4.0.2](https://github.com/wessberg/compatfactory/compare/v4.0.1...v4.0.2) (2024-09-25)

### Bug Fixes

- export- and import declaration bugs on TS 5.2 ([b5b9223](https://github.com/wessberg/compatfactory/commit/b5b92231e3fc33d8d69ff77684edfb23eafd46b9))

## [4.0.1](https://github.com/wessberg/compatfactory/compare/v4.0.0...v4.0.1) (2024-09-24)

### Bug Fixes

- handle export declarations on TS v4.8 and 4.9 ([b05744c](https://github.com/wessberg/compatfactory/commit/b05744ce495fee96a99267de8ccff2bc1f610bf4))

# [4.0.0](https://github.com/wessberg/compatfactory/compare/v3.0.0...v4.0.0) (2024-09-24)

### Features

- add TypeScript v5.2.2 compatibility ([8090a3d](https://github.com/wessberg/compatfactory/commit/8090a3dc32d6925c5f572c9f75e8609ae94a2699))
- add TypeScript v5.3 support ([4542219](https://github.com/wessberg/compatfactory/commit/4542219a5b5198cf16d3eaa1934aad0f8ea8572c))
- add TypeScript v5.5 support ([feefd1b](https://github.com/wessberg/compatfactory/commit/feefd1b77a1bff9a50faa58dc24b682589eaa591))
- add TypeScript v5.6 support ([e941e67](https://github.com/wessberg/compatfactory/commit/e941e67d3de957fadc964e84a9871d37fd4b5fa5))

# [3.0.0](https://github.com/wessberg/compatfactory/compare/v2.0.9...v3.0.0) (2023-08-01)

### Bug Fixes

- allow TypeScript@5 and newer as peer dependency ([68cf1e7](https://github.com/wessberg/compatfactory/commit/68cf1e71f4ca6e1455cc075d3a18ef03f2293abf))
- update docs ([865d43a](https://github.com/wessberg/compatfactory/commit/865d43a9e2b72abd2f9bd6a03ab51630d9de028b))

### Features

- add support for TypeScript v5.1 ([1b1111c](https://github.com/wessberg/compatfactory/commit/1b1111c7e1595f941d9d9781d2a23a0d5f08f8a1))

## [2.0.9](https://github.com/wessberg/compatfactory/compare/v2.0.8...v2.0.9) (2023-01-09)

### Bug Fixes

- set undefined instead of empty array as decorators for all TS versions ([905175e](https://github.com/wessberg/compatfactory/commit/905175e43b803dd1cb948f63e025478036a79c81))

## [2.0.8](https://github.com/wessberg/compatfactory/compare/v2.0.7...v2.0.8) (2023-01-09)

### Bug Fixes

- fix issue with updateImportEqualsDeclaration on TypeScript 3.x ([c5a67b8](https://github.com/wessberg/compatfactory/commit/c5a67b879bf5cac7f0f1d76f99626852afa1f157))

## [2.0.7](https://github.com/wessberg/compatfactory/compare/v2.0.6...v2.0.7) (2023-01-09)

### Bug Fixes

- implement compat handling for createTypeParameterDeclaration with or without modifiers as first argument ([d87f910](https://github.com/wessberg/compatfactory/commit/d87f910223e2a45e730b8a2b58f25b61ea464ce9))

## [2.0.6](https://github.com/wessberg/compatfactory/compare/v2.0.5...v2.0.6) (2023-01-09)

### Bug Fixes

- fix issues with overloads ([acc70eb](https://github.com/wessberg/compatfactory/commit/acc70eb4bc894b88f72c87093992962a29d69574))

## [2.0.5](https://github.com/wessberg/compatfactory/compare/v2.0.4...v2.0.5) (2023-01-09)

### Bug Fixes

- add missing overloaded signatures ([95a6eee](https://github.com/wessberg/compatfactory/commit/95a6eee5fc0fe21b8541cc96eae63919a5fb0372))

## [2.0.4](https://github.com/wessberg/compatfactory/compare/v2.0.3...v2.0.4) (2023-01-09)

### Bug Fixes

- fix issue with overloaded arguments ([45a7456](https://github.com/wessberg/compatfactory/commit/45a7456f2c455ce2f8dffee66632bb8a23e3dca6))

## [2.0.3](https://github.com/wessberg/compatfactory/compare/v2.0.2...v2.0.3) (2023-01-09)

### Bug Fixes

- fix issue with constructing ClassStaticDeclarations ([4370bfd](https://github.com/wessberg/compatfactory/commit/4370bfdae6ed1588dd452a60dd3d0710da7638cd))

## [2.0.2](https://github.com/wessberg/compatfactory/compare/v2.0.1...v2.0.2) (2023-01-09)

### Bug Fixes

- correctly split decorators and modifiers ([5cb9b93](https://github.com/wessberg/compatfactory/commit/5cb9b9301b050f85a4d8a604cf2ecf353d01f35c))

## [2.0.1](https://github.com/wessberg/compatfactory/compare/v2.0.0...v2.0.1) (2023-01-09)

### Bug Fixes

- resolve issues with import declarations ([6efb703](https://github.com/wessberg/compatfactory/commit/6efb703bd2aff6e8e8fc1c297afcff825ae64a83))

# [2.0.0](https://github.com/wessberg/compatfactory/compare/v1.0.1...v2.0.0) (2023-01-09)

### Bug Fixes

- fix lint ([3408a0d](https://github.com/wessberg/compatfactory/commit/3408a0dd93719ade333f08fb83926b151c0103a3))

### Features

- add support for TypeScript v4.8 ([05020b8](https://github.com/wessberg/compatfactory/commit/05020b85fd72dc5c305463bf68804fde26a0d74a))
- add support for TypeScript v4.9 ([4d157b3](https://github.com/wessberg/compatfactory/commit/4d157b31f29048ebbb81724eda414c1298f6aebe))

## [1.0.1](https://github.com/wessberg/compatfactory/compare/v1.0.0...v1.0.1) (2022-05-30)

### Features

- add support for passing in 5 arguments to creatImportTypeNode on all versions of TypeScript ([9ae49d6](https://github.com/wessberg/compatfactory/commit/9ae49d6c11cfd2093c8de3bb8878f75ed07b92ca))

# [1.0.0](https://github.com/wessberg/compatfactory/compare/v0.0.13...v1.0.0) (2022-05-29)

## [0.0.13](https://github.com/wessberg/compatfactory/compare/v0.0.12...v0.0.13) (2022-04-12)

## [0.0.12](https://github.com/wessberg/compatfactory/compare/v0.0.11...v0.0.12) (2021-11-17)

### Bug Fixes

- ensure that createExportSpecifier can be called with three arguments across all TypeScript versions ([aad253d](https://github.com/wessberg/compatfactory/commit/aad253ddd5a2d7442a792a66d9e4d7353cabb96a))

## [0.0.11](https://github.com/wessberg/compatfactory/compare/v0.0.10...v0.0.11) (2021-11-17)

### Bug Fixes

- ensure that createImportSpecifier can be called with three arguments across all TypeScript versions ([cd840b0](https://github.com/wessberg/compatfactory/commit/cd840b093f9f2d01eda3bd7cf766a1d443dcb2d5))

## [0.0.10](https://github.com/wessberg/compatfactory/compare/v0.0.9...v0.0.10) (2021-11-17)

### Features

- add TypeScript v4.5 support ([2d33062](https://github.com/wessberg/compatfactory/commit/2d33062a4a840644aae884b258d4a8e0ffa38a43))

## [0.0.9](https://github.com/wessberg/compatfactory/compare/v0.0.8...v0.0.9) (2021-08-30)

### Features

- add support for TypeScript v4.4 and add more compatibility fixes ([285ae96](https://github.com/wessberg/compatfactory/commit/285ae96bd83c1420fe7ff1b8130ab72eaf7370f8))

## [0.0.8](https://github.com/wessberg/compatfactory/compare/v0.0.7...v0.0.8) (2021-06-11)

### Features

- **property-access-chain:** add compatibility for TypeScript < 3.6 when generating PropertyAccessChains ([909ab22](https://github.com/wessberg/compatfactory/commit/909ab22084c9070b1bb974c281c5c7b9a0548a76))

## [0.0.7](https://github.com/wessberg/compatfactory/compare/v0.0.6...v0.0.7) (2021-05-29)

### Bug Fixes

- use provided modifiers when creating/updating MethodSignatures ([cfac75f](https://github.com/wessberg/compatfactory/commit/cfac75fcd593384d5d3b1c1a4066f5f769f50eaf))

## [0.0.6](https://github.com/wessberg/compatfactory/compare/v0.0.5...v0.0.6) (2021-05-29)

### Bug Fixes

- allow passing an already wrapped TypeScript object to ensureNodeFactory without performing any additional wrapping ([913abb8](https://github.com/wessberg/compatfactory/commit/913abb8f7e7218876013a5f3cf48dd3f748f404e))

## [0.0.5](https://github.com/wessberg/compatfactory/compare/v0.0.4...v0.0.5) (2021-05-29)

### Bug Fixes

- fix signature for createVariableDeclaration ([a311bc1](https://github.com/wessberg/compatfactory/commit/a311bc17ca73c8d899f160afed606f6ef49d3fa5))

## [0.0.4](https://github.com/wessberg/compatfactory/compare/v0.0.3...v0.0.4) (2021-05-28)

### Features

- add additional JSDoc factory functions for older TypeScript versions ([99ced96](https://github.com/wessberg/compatfactory/commit/99ced9601698114282b4a57c1d3afec6fc51c960))

## [0.0.3](https://github.com/wessberg/compatfactory/compare/v0.0.2...v0.0.3) (2021-05-28)

### Features

- unify signatures for createImportEqualsDeclaration and createMappedTypeNode with latest TypeScript versions for TypeScript <4 ([ed7e4e0](https://github.com/wessberg/compatfactory/commit/ed7e4e07e11749f487ad7663e6a5e662f34f9c8f))

## [0.0.2](https://github.com/wessberg/compatfactory/compare/v0.0.1...v0.0.2) (2021-05-28)

### Features

- unify signatures for createImportEqualsDeclaration and createMappedTypeNode with latest TypeScript versions for v4.0 and v4.1 ([a4e3f5f](https://github.com/wessberg/compatfactory/commit/a4e3f5f9b04108f0c1d188ed6a3d5eff689aff09))

## 0.0.1 (2021-05-28)
