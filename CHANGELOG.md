# dbt-trino Changelog

- This file provides a full account of all changes to `dbt-trino`
- Changes are listed under the (pre)release in which they first appear. Subsequent releases include changes from previous releases.
- "Breaking changes" listed under a version may require action from end users or external maintainers when upgrading to that version.
- Do not edit this file directly. This file is auto-generated using [changie](https://github.com/miniscruff/changie). For details on how to document a change, see [the contributing guide](https://github.com/starburstdata/dbt-trino/blob/master/CONTRIBUTING.md#adding-changelog-entry)
## dbt-trino 1.6.1 - August 09, 2023
### Fixes
- Implemented fetchmany ([#341](https://github.com/starburstdata/dbt-trino/pull/341))

### Contributors
- [@damian3031](https://github.com/damian3031) ([#341](https://github.com/starburstdata/dbt-trino/pull/341))
## dbt-trino 1.6.0 - August 01, 2023
### Breaking Changes
- Drop support for Python 3.7 ([#314](https://github.com/starburstdata/dbt-trino/issues/314), [#331](https://github.com/starburstdata/dbt-trino/pull/331))
- Update dbt-core to 1.6.0 ([#332](https://github.com/starburstdata/dbt-trino/pull/332))
- Renamed relation type 'materializedview' to 'materialized_view' to be consistent with dbt-core 1.6. If you have any custom macro where you check if relation type equals to 'materializedview', change it to 'materialized_view' ([#332](https://github.com/starburstdata/dbt-trino/pull/332))
### Under the Hood
- Refactored materialized view macros ([#333](https://github.com/starburstdata/dbt-trino/pull/333))
- Add new tests from dbt-tests-adapter ([#335](https://github.com/starburstdata/dbt-trino/pull/335))
- Add schema teardown method where necessary ([#267](https://github.com/starburstdata/dbt-trino/issues/267), [#335](https://github.com/starburstdata/dbt-trino/pull/335))
### Dependencies
- Update dbt-tests-adapter requirement from ~=1.5.2 to ~=1.6.0 ([#330](https://github.com/starburstdata/dbt-trino/pull/330))

### Contributors
- [@damian3031](https://github.com/damian3031) ([#331](https://github.com/starburstdata/dbt-trino/pull/331), [#332](https://github.com/starburstdata/dbt-trino/pull/332), [#332](https://github.com/starburstdata/dbt-trino/pull/332), [#333](https://github.com/starburstdata/dbt-trino/pull/333), [#335](https://github.com/starburstdata/dbt-trino/pull/335), [#335](https://github.com/starburstdata/dbt-trino/pull/335))
- [@dependabot[bot]](https://github.com/dependabot[bot]) ([#330](https://github.com/starburstdata/dbt-trino/pull/330))
## Previous Releases

For information on prior major and minor releases, see their changelogs:

* [1.5](https://github.com/starburstdata/dbt-trino/blob/1.5.latest/CHANGELOG.md)
* [1.4](https://github.com/starburstdata/dbt-trino/blob/1.4.latest/CHANGELOG.md)
* [1.3](https://github.com/starburstdata/dbt-trino/blob/1.3.latest/CHANGELOG.md)
* [1.2](https://github.com/starburstdata/dbt-trino/blob/1.2.latest/CHANGELOG.md)
* [1.1](https://github.com/starburstdata/dbt-trino/blob/1.1.latest/CHANGELOG.md)
* [1.0 and earlier](https://github.com/starburstdata/dbt-trino/blob/1.0.latest/CHANGELOG.md)
