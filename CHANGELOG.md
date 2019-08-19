# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project tries to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.8.2 / 2019-08-19

### Changed

- Started following the [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) standard
- Minor cosmetic change: Readme.md updated with shield.io badges
- Changelog format updated

## 0.8.0 - 0.8.1 / 2018-01-08

- Stop using mondogb promise libraries and use the native mongodb promises
- Updated documentation.

## 0.7.0 - 0.7.3 / 2018-01-03

- Add `rollback` command to migrate down just the last applied migration
- Better logs in migrations

## 0.6.0 - 0.6.3 / 2018-01-02

- Mongo library changed from [promised-mongo](https://github.com/gordonmleigh/promised-mongo) to [then-mongo](https://github.com/then/then-mongo)

## 0.5.0, 0.5.1 / 2018-01-02

- Project forked to [neverbot/node-mongodb-migrations](https://github.com/neverbot/node-mongodb-migrations)
- Set renamed as CoreSet to avoid name collisions
- jshint review
- Log migration times

## 0.4.0 / 2016-10-06

- Add a comment about state-mongo usage

## 0.3.1 / 2016-09-25

- Allow sync between migration file and migration collection

## 0.3.0 / 2016-09-22

- Project forked to [ikatun/node-migrate](https://github.com/ikatun/node-migrate)
- Add `--state-db` option to persist changes to DB instead of file

## 0.2.3 / 2016-07-05

- Add date-format option for new migrations (#66)
- Update readme: Usage section (#65)
- Add missing license field to package.json (#64)

## 0.2.2 / 2015-07-07

- Fixed migration to specific point by name

## 0.2.1 / 2015-04-24

- Ability to use a custom template file
- Expose easy api for programmatic use
- State is now saved after each successful migration
- Proper tests with `mocha`
- Add `use strict` to the template

## 0.2.0 / 2014-12-26

- Report errors on migration next
- The name format of migrations is now timestamp-based instead of numerical
- Remove inner library version

## 0.1.6 / 2014-10-28

- Fix paths for windows users
- Added command line option --state-file (to set the location of the migration state file)

## 0.1.3 / 2012-06-25

- Update migrate to support v0.8.x

## 0.1.2 / 2012-03-15

- 0.7.x support

## 0.1.1 / 2011-12-04

- Fixed a typo [kishorenc]

## 0.1.0 / 2011-12-03

- Added support for incremental migrations. [Kishore Nallan]

## 0.0.5 / 2011-11-07

- 0.6.0 support

## 0.0.4 / 2011-09-12

- Fixed: load js files only [aheckmann]

## 0.0.3 / 2011-09-09

- Fixed initial `create` support

## 0.0.2 / 2011-09-09

- Fixed `make test`

## 0.0.1 / 2011-04-24

- Initial release
