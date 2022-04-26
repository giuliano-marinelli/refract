# Changelog

## [1.0.10]

- Adds `Raw` decorator escape hatch, similar to `.Raw()` model method
  - Can now do `Raw('@db.ObjectId')` etc to use un-supported decorators
- Fixes some out of date documentation

## [1.0.9]

- Adds `Map` decorator (e.g. `@map("foo")`)
- Renames `Varchar` to `String`
- Renames `Index` to `Id`
  - Adds `cuid()`, `uuid()`
- Adds `Ignore` decorator (e.g. `@ignore`)
- Adds `Float`, `BigInt`, `Bytes`, `Decimal` scalars
- Refactors how Enums are created
  - Adds `Key`
  - Enums definitions can now have decorators
- Refactors types on data-types to be more specific

## [1.0.8]

## [1.0.7]

## [1.0.6]

- Fix issue with `Enum` codegen always being nullable when having >=1 modifier
- Improve documentation

## [1.0.5]

- Useage documentation
- Added CI testing

## [1.0.4]

- Removed field checking on relationships because of fails with circular relationships

## [1.0.3]

- Added block alignment
- Added `OneToOne()` relationships

## [1.0.2]

- Added `.Raw()` Prisma escape hatch
- Added `.Mixin()` utility field

## [1.0.1]

- Added enums

## [1.0.0]

- Initial release