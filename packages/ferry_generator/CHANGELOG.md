## 0.14.0-dev.0

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**(ferry_generator): upgrade to latest gql_code_builder (#637).
 - **BREAKING** **FEAT**(ferry_generator): upgrade gql_code_builder to 0.14.0.

## 0.13.0

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**(ferry_generator): upgrade gql_code_builder to 0.14.0.

## 0.12.1-dev.2

 - **FEAT**(ferry_generator): support analyzer ^7.0.0 (#635).

## 0.12.1-dev.1

 - **FEAT**(ferry_generator): allow analyzer 7.3.0 (#634).

## 0.12.1-dev.0

 - **FEAT**(ferry_generator): move to dart_style 3.0.0 (#632).

## 0.12.0+2

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 0.12.0-dev.0+2

 - Update a dependency to the latest release.

## 0.12.0+1

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 0.12.0-dev.0+1

 - **REFACTOR**(ferry_generator): Add const constructor to AddTypenameField.

## 0.12.0

 - **FEAT**(ferry_generator): external schema import (#606).

## 0.12.0-dev.1

 - **DOCS**(ferry_generator): add docs for new dependency.

## 0.12.0-dev.0

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**(ferry_generator): update to gql_code_builders 0.12.0. this extracted the common serializers to a separate package. clients need to add gql_code_builder_serializers to their dependencies if they use ferry_generator. (#601).

## 0.10.0-dev.2

 - **FEAT**(ferry_generator): Passing through builder options to schema builder (#585).

## 0.10.0-dev.1

 - Update a dependency to the latest release.

## 0.10.0-dev.0+1

 - Update a dependency to the latest release.

## 0.10.0

- **FEAT**: pass context to gql links.

## 0.9.1-dev.1

- **FEAT**(vars-builder-generator): Adding documentation for new codegen options.

## 0.9.1-dev.0

- Bump "ferry_generator" to `0.9.1-dev.0`.

## 0.9.1

- Bump "ferry_generator" to `0.9.1`.

## 0.9.0-dev.2

- **FEAT**(ferry_generator): allow analyzer 6.0.

## 0.9.0-dev.1

> Note: This release has breaking changes.

- **BREAKING** **FEAT**(ferry_generator): make dataToJson() method type safe by using the generic
  data type instead of dynamic.

## 0.9.0-dev.0+1

- **DOCS**: add topics (#548)
- **FEAT**(ferry_generator): support adding `tristate_optionals: true` in the config of build.yaml
  in your graphql_builder in order to wrap nullable fields into a Value type in order to distinguish
  between absent and null values in inputs (#549).

## 0.8.2-dev.0+1

- **DOCS**: add topics (#548).

## 0.8.2

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.8.2-dev.2

> Note: This release has breaking changes.

- **BREAKING** **FEAT**(ferry_exec): remove usage of dynamic in cache and AddTypeNameTypedLink by
  adding new methods to operationrequest  (#547).

## 0.8.2-dev.1

- **FEAT**(ferry_generator): experimental: add option to reuse data classes for fragments with a
  single inline fragment spread as selection (#530).

## 0.8.2-dev.0

- **FEAT**(ferry_generator): experimental support for multiple schemas (#518).

## 0.8.1

- **FEAT**: support stable 1.0.0 versions of depenencies gql, gql_exec, gql_link (#521).

## 0.8.0-dev.5

> Note: This release has breaking changes.

- **FIX**: Use Posix separators for output paths (#369).
- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **FEAT**: support stable 1.0.0 versions of depenencies gql, gql_exec, gql_link (#521).
- **FEAT**(ferry_generator): when/maybeWhen extensions (#470).
- **FEAT**(ferry): add IsolateClient (#405).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.8.0-dev.4

> Note: This release has breaking changes.

- **FIX**: Use Posix separators for output paths (#369).
- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **FEAT**: support stable 1.0.0 versions of depenencies gql, gql_exec, gql_link (#521).
- **FEAT**(ferry_generator): when/maybeWhen extensions (#470).
- **FEAT**(ferry): add IsolateClient (#405).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.8.0-dev.3

> Note: This release has breaking changes.

- **FIX**: Use Posix separators for output paths (#369).
- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **FEAT**(ferry_generator): when/maybeWhen extensions (#470).
- **FEAT**(ferry): add IsolateClient (#405).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).
- **DOCS**(website): improve custom scalars documention (#517).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.8.0-dev.2

> Note: This release has breaking changes.

- **FIX**: Use Posix separators for output paths (#369).
- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **FEAT**(ferry_generator): when/maybeWhen extensions (#470).
- **FEAT**(ferry): add IsolateClient (#405).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.8.0-dev.1

> Note: This release has breaking changes.

- **FIX**: Use Posix separators for output paths (#369).
- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **FEAT**(ferry_generator): when/maybeWhen extensions (#470).
- **FEAT**(ferry): add IsolateClient (#405).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).
- **BREAKING** **FIX**(ferry_generator): properly generate nullable types for nullable elements in
  Lists (#445).
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.8.0-dev.0+2

- **DOCS**: add basic documentation for field policy (#494).

## 0.8.0+1

- Update a dependency to the latest release.

## 0.8.0

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.8.0-dev.3

- Update a dependency to the latest release.

## 0.8.0-dev.2

- Update a dependency to the latest release.

## 0.8.0-dev.1

- **FEAT**: when/maybeWhen extensions (#470).
- **FEAT**: add when()/maybeWhen() extension methods on infline fragment spreads with type
  condidtion.

## 0.8.0-dev.0

* Add support for generating `when()` and `maybeWhen()` methods inline fragment
  spreads with a type condition in order to access the fields of the inline
  fragment spread without casting. Requires `add_typenames` to be `true` in
  the build.yaml config (it's `true` by default).
  To enable, add

```yaml
          when_extensions:
            when: true
            maybeWhen: true
```

To the `options` section of the `ferry_generator` config in `build.yaml`.

## 0.7.0

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.7.0-dev.0

> Note: This release has breaking changes.

- **BREAKING** **FIX**: properly generate nullable types for nullable elements in Lists (#445).

## 0.6.1

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.6.1-dev.1

- Update a dependency to the latest release.

## 0.6.1-dev.0

- **FEAT**: add IsolateClient (#405).

## 0.6.0+1

- Update a dependency to the latest release.

## 0.6.0

- **FIX**: Use Posix separators for output paths (#369).
- **FEAT**: generate possibleTypesMap in ferry_generator (#371).

## 0.6.0-dev.1

> Note: This release has breaking changes.

- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.5.0-dev.10

> Note: This release has breaking changes.

- **FIX**: revert broken transitive dependency.
- **FIX**: upgrade analyzer dependency.
- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **BREAKING** **CHORE**: update gql_code_builder, gql_exec and vestigial analyzer pubspec entry.

## 0.5.0-dev.9

- Update a dependency to the latest release.

## 0.5.0-dev.8

- **DOCS**: remove stale code (#271).

## 0.5.0-dev.7

- **FIX**: add dispose method to TypedLinks (#272).

## 0.5.0-dev.6

- **FIX**: add missing dependencies (#268).

## 0.5.0-dev.5

- **FIX**: add missing dependencies (#267).

## 0.5.0-dev.4

- **FIX**: add missing override annotations (#261).

## 0.5.0-dev.3

- **FEAT**: add github action for validating formatting (#260).

## 0.5.0-dev.2

- **FEAT**: add extensions to response (#259).

## 0.5.0-dev.1

> Note: This release has breaking changes.

- **BREAKING** **FEAT**: build generated files to __generated__ subdirectory.

## 0.5.0-dev.0

> Note: This release has breaking changes.

- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **BREAKING** **FEAT**: build generated files to __generated__ subdirectory.

## 0.4.4-dev.0+1

- **FIX**: move pedantic to dependency (#257).

## 0.4.4

- **FEAT**: update dependences.
- **FEAT**: update dependences.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.4.3

- **FEAT**: update dependences.
- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.4.2

- **FEAT**: migrate to null safety.
- **FEAT**: migrate to null safety.
- **CHORE**: publish packages.
- **CHORE**: publish packages.

## 0.4.1

- Graduate package to a stable release. See pre-releases prior to this version for changelog
  entries.

## 0.4.1-0.1.nullsafety.1

- **FIX**: update build_runner.

## 0.4.1-0.1.nullsafety.0

- **FEAT**: migrate to null safety.
- **CHORE**: bump versions to match melos style.
- **CHORE**: publish packages.
- **CHORE**: prepare changelogs for melos.

## 0.4.0-1.0.nullsafety.0

- **FEAT**: migrate to null safety.
- **CHORE**: prepare changelogs for melos.

## [0.4.0-nullsafety.1]

- allow fragment names to be nullable

## [0.4.0-nullsafety.0]

- initial null safety support

## [0.3.3]

- update dependencies

## [0.3.2] - 2020-12-06

### Changed

- bump `gql_build` and `gql_code_builder` versions

## [0.3.1] - 2020-11-09

### Changed

- don't assign default `OperationRequest.requestId`s

### Removed

- remove `uuid` dependency

## [0.3.0] - 2020-10-11

### Changed

- use `ferry_exec`
- add `executeOnListen` default value

## [0.2.1] - 2020-09-08

### Changed

- use latest `gql_build`

## [0.2.0] - 2020-08-24

### Added

- Add generated `FragmentRequest`s

### Changed

- bump `gql_build` & `gql_code_builder` versions
- rename `QueryRequest` to `OperationRequest`
- assign a default `OperationRequest.requestId` using the `uuid` package

## [0.1.0] - 2020-05-10

### Added

- initial release as an independent package
