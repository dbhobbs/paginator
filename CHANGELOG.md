# Changelog

## v0.3.1 - 2018-02-20

### Fixed

* Fix bug for queries with a pre-existing `where` clause. Sometimes, this clause
ended up being combined with the pagination filter using an `OR`.

## v0.3.0 - 2018-02-14

### Added

* `:limit` is now capped by `:maximum_limit`. By default, `:maximum_limit` is set
to 500.

## v0.2.0 - 2018-02-13

### Added

* `:total_count_limit` can be set to `:infinity` to return the accurate count of
records.

## v0.1.0 - 2018-02-13

Initial release! 🎉
