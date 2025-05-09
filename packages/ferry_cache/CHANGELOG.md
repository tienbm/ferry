## 0.10.1-dev.0+1

 - Update a dependency to the latest release.

## 0.10.1

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 0.10.1-dev.1

 - Update a dependency to the latest release.

## 0.10.1-dev.0

 - **FEAT**(ferr_cache): add evict operation.

## 0.10.0+1

 - Update a dependency to the latest release.

## 0.10.0

## 0.10.0-dev.0

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**(ferry_generator): update to gql_code_builders 0.12.0. this extracted the common serializers to a separate package. clients need to add gql_code_builder_serializers to their dependencies if they use ferry_generator. (#601).
 - **BREAKING** **CHORE**(deps): upgrade rxdart to v0.28.0 (#612).

## 0.9.0

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 0.9.0-dev.4

 - Update a dependency to the latest release.

## 0.9.0-dev.3

> Note: This release has breaking changes.

 - **BREAKING** **CHORE**(deps): upgrade rxdart to v0.28.0 (#612).

## 0.9.0-dev.2

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**(ferry_generator): update to gql_code_builders 0.12.0. this extracted the common serializers to a separate package. clients need to add gql_code_builder_serializers to their dependencies if they use ferry_generator. (#601).

## 0.9.0-dev.1

 - Update a dependency to the latest release.

## 0.9.0-dev.0+2

 - Update a dependency to the latest release.

## 0.9.0+1

 - Update a dependency to the latest release.

## 0.9.0

- Update a dependency to the latest release.

## 0.8.0-dev.2

- Update a dependency to the latest release.

## 0.8.0-dev.1

- **FEAT**(ferry_generator): support adding in the config of build.yaml in your graphql_builder in
  order to wrap nullable fields into a Value type in order to distinguish between absent and null
  values in inputs (#549).

## 0.8.0-dev.0+1

- **DOCS**: add topics (#548).

## 0.8.0

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.8.0-dev.0

> Note: This release has breaking changes.

- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FEAT**(ferry_generator): add option to reuse data classes for fragments with a single inline
  fragment spread as selection (#530).
- **BREAKING** **FEAT**(ferry_exec): remove usage of dynamic in cache and AddTypeNameTypedLink by
  adding new methods to operationrequest  (#547).

## 0.7.1-dev.6

> Note: This release has breaking changes.

- **FEAT**(ferry_generator): add option to reuse data classes for fragments with a single inline
  fragment spread as selection (#530).
- **BREAKING** **FEAT**(ferry_exec): remove usage of dynamic in cache and AddTypeNameTypedLink by
  adding new methods to operationrequest  (#547).

## 0.7.1-dev.5

> Note: This release has breaking changes.

- **FEAT**(ferry_generator): add option to reuse data classes for fragments with a single inline
  fragment spread as selection (#530).
- **BREAKING** **FEAT**(ferry_exec): remove usage of dynamic in cache and AddTypeNameTypedLink by
  adding new methods to operationrequest  (#547).

## 0.7.1-dev.4

- **FEAT**(ferry_generator): add option to reuse data classes for fragments with a single inline
  fragment spread as selection (#530).

## 0.7.1-dev.3

- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FEAT**(ferry_generator): add option to reuse data classes for fragments with a single inline
  fragment spread as selection (#530).

## 0.7.1-dev.2

- **REFACTOR**: apply lints fixes (#479).
- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.

## 0.7.1-dev.1

- Update a dependency to the latest release.

## 0.7.1-dev.0+3

- Update a dependency to the latest release.

## 0.7.1+2

- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.

## 0.7.1-dev.8

- Update a dependency to the latest release.

## 0.7.1-dev.7

> Note: This release has breaking changes.

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.6

> Note: This release has breaking changes.

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**: support stable 1.0.0 versions of depenencies gql, gql_exec, gql_link (#521).
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.5

> Note: This release has breaking changes.

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **DOCS**(website): improve custom scalars documention (#517).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.4

> Note: This release has breaking changes.

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(normalize): When there are dangling references in child objects of a list, by default do
  not treat the whole entity as partial data, but remove it from the list. This can be configured
  using the allowDanglingReference parameter.
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.3

> Note: This release has breaking changes.

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.2

> Note: This release has breaking changes.

- **REFACTOR**(ferry_cache): use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid
  it's O(n^2) complexity, remove duplicated .distinct() call (#477).
- **FIX**(ferry_cache): ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).
- **FIX**(ferry_cache): fix cache emits update too often (#411).
- **FIX**(ferry_cache): fix regression in watch() methods by making changeStream emit when new item
  is added to the cache (#403).
- **FIX**(cache): Fix memory leak. (#385).
- **FIX**: add possibleTypes to every function that can use it of normalize (#380).
- **FIX**: pin normalize 0.6.0.
- **FEAT**(ferry_hive_store): use jsonMapEquals instead of DeepCollectionEquality().equals to avoid
  it's O(n^2) complexity, add distinct: param to watch() method (#475).
- **FEAT**(ferry_cache): add `clearOptimisticPatches()` (#459).
- **FEAT**(ferry): add IsolateClient (#405).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).

## 0.7.1-dev.1

- **FIX**: When there are dangling references in child objects of a list, by default do not treat
  the whole entity as partial data, but remove it from the list. This can be configured using the
  allowDanglingReference parameter.

## 0.7.1-dev.0+2

- **DOCS**: add basic documentation for field policy (#494).

## 0.7.1+1

- Update a dependency to the latest release.

## 0.7.1

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.7.1-dev.2

- **REFACTOR**: apply lints fixes (#479).

## 0.7.1-dev.1

- **REFACTOR**: apply lints fixes (#479).
- **REFACTOR**: use jsonMapEquals instead of DeepCollectionEquality.equals() to avoid it's O(n^2)
  complexity, remove duplicated .distinct() call (#477).
- **FEAT**: use jsonMapEquals instead of DeepCollectionEquality().equals to avoid it's O(n^2)
  complexity, add distinct: param to watch() method (#475).

## 0.7.1-dev.0

- **FEAT**: add `clearOptimisticPatches()` (#459).

## 0.7.0

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.7.0-dev.0

> Note: This release has breaking changes.

- **BREAKING** **FIX**: properly generate nullable types for nullable elements in Lists (#445).

## 0.6.4

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.6.4-dev.0

## 0.6.4

## 0.6.3-dev.1

- **FIX**: ensure emitting only one update per updated data ID in cache in
  watchQuery/watchFragment (#416).

## 0.6.3-dev.0

- **FIX**: fix cache emits update too often (#411).
- **FIX**: fix regression in watch() methods by making changeStream emit when new item is added to
  the cache (#403).
- **FEAT**: add IsolateClient (#405).

## 0.6.2+1

- Update a dependency to the latest release.

## 0.6.2

- fix(ferry_cache): fix memory leak when calling .watch()

- **FIX**: Fix memory leak. (#385).

## 0.6.1+1

- Update a dependency to the latest release.

## 0.6.1

- FIX: add missing possibleTypes parameters to calls to normlalize

- **FIX**: add possibleTypes to every function that can use it of normalize (#380).

## 0.6.0

- bump normalize dependency version constraint to fix fragment disambiguation

- **FIX**: pin normalize 0.6.0.

## 0.5.5-dev.10

- Update a dependency to the latest release.

## 0.5.5-dev.9

- Update a dependency to the latest release.

## 0.5.5-dev.8

- **DOCS**: remove stale code (#271).

## 0.5.5-dev.7

- **FIX**: add dispose method to TypedLinks (#272).

## 0.5.5-dev.6

- **FIX**: add missing dependencies (#268).

## 0.5.5-dev.5

- **FIX**: add missing dependencies (#267).

## 0.5.5-dev.4

- **FIX**: add missing override annotations (#261).

## 0.5.5-dev.3

- **FEAT**: add github action for validating formatting (#260).

## 0.5.5-dev.2

- **FEAT**: add extensions to response (#259).

## 0.5.5-dev.1

> Note: This release has breaking changes.

- **BREAKING** **FEAT**: build generated files to __generated__ subdirectory.

## 0.5.5-dev.0+1

- **FIX**: move pedantic to dependency (#257).

## 0.5.5

- **FEAT**: update dependences.
- **FEAT**: update dependences.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.5.4

- **FEAT**: update dependences.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.5.3+1

- **FIX**: Supply empty possibleTypeOf map `operationFieldNames`.
- **FIX**: resolve issue with data change streams.
- **FIX**: resolve issue with data change streams.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.5.3

- add support for `dataIdFromObject`
- bump `normalize` version

## 0.5.2+1

- **FIX**: resolve issue with data change streams.
- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.5.2

- **FEAT**: migrate to null safety.
- **FEAT**: migrate to null safety.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.5.1

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.5.1-0.1.nullsafety.0

- **FEAT**: migrate to null safety.
- **CHORE**: bump versions to match melos style.
- **CHORE**: publish packages.
- **CHORE**: prepare changelogs for melos.

## 0.5.0-1.0.nullsafety.0

- **FEAT**: migrate to null safety.
- **CHORE**: prepare changelogs for melos.

## [0.5.0-nullsafety.0]

- add initial support for null safety

## [0.4.3]

- update internal watch logic
- add `watchFragment` method

## [0.4.2]

- update dependencies

## [0.4.1] - 2020-11-15

### Added

- Allow `evict()` method to accept an `optimisticRequest`
- Add tests

## [0.4.0] - 2020-11-09

### Changed

- use the entire `OperationRequest`, not just the `requestId` as the key in optimistic patches map
- `writeQuery` and `writeFragment` now accept the optimistic request itself instead of just the
  requestId
- bump `normalize` version

### Removed

- move `deepMerge` to a utility function in `normalize` package

## [0.3.0] - 2020-10-10

### Added

- move cache pack to seperate package
- return keys to remove from `Cache.gc()`
- upgrade `rxdart` to latest version
