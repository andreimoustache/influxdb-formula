# Changelog

## [0.3.2](https://github.com/saltstack-formulas/influxdb-formula/compare/v0.3.1...v0.3.2) (2019-10-12)


### Bug Fixes

* **rubocop:** add fixes using `rubocop --safe-auto-correct` ([](https://github.com/saltstack-formulas/influxdb-formula/commit/a9245c2))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/influxdb-formula/commit/b8049e2))
* **travis:** merge `rubocop` linter into main `lint` job ([](https://github.com/saltstack-formulas/influxdb-formula/commit/84c5486))

## [0.3.1](https://github.com/saltstack-formulas/influxdb-formula/compare/v0.3.0...v0.3.1) (2019-10-10)


### Bug Fixes

* **map.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/influxdb-formula/commit/d7b9682))


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([](https://github.com/saltstack-formulas/influxdb-formula/commit/cbf8691))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/influxdb-formula/commit/a4718ee))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/influxdb-formula/commit/6690ed8))
* **kitchen+travis:** replace EOL pre-salted images ([](https://github.com/saltstack-formulas/influxdb-formula/commit/8d1a0ae))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([](https://github.com/saltstack-formulas/influxdb-formula/commit/c651f74))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([](https://github.com/saltstack-formulas/influxdb-formula/commit/ecfe10d))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/influxdb-formula/commit/9f4f588))
* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([](https://github.com/saltstack-formulas/influxdb-formula/commit/e36e78a))

# [0.3.0](https://github.com/saltstack-formulas/influxdb-formula/compare/v0.2.1...v0.3.0) (2019-08-25)


### Bug Fixes

* **gemfile:** don't put Gemfile.lock in repo ([c20c491](https://github.com/saltstack-formulas/influxdb-formula/commit/c20c491))
* **install:** fix systemd unit install on Suse ([94c5367](https://github.com/saltstack-formulas/influxdb-formula/commit/94c5367))
* **state:** fix int comparison ([4874c05](https://github.com/saltstack-formulas/influxdb-formula/commit/4874c05))
* **states:** use curl instead of wget (not installed everywhere) ([cfdfc38](https://github.com/saltstack-formulas/influxdb-formula/commit/cfdfc38))


### Code Refactoring

* **kitchen:** sync Kitchene file with template-formula ([5d40aec](https://github.com/saltstack-formulas/influxdb-formula/commit/5d40aec))


### Continuous Integration

* **travis:** default-debian-9-develop-py3 is buggy ([ec3e57d](https://github.com/saltstack-formulas/influxdb-formula/commit/ec3e57d))
* **travis:** re-enable tests on default-debian-9-develop-py3 ([70f8d6f](https://github.com/saltstack-formulas/influxdb-formula/commit/70f8d6f))
* **travis:** run tests first ([13a55a7](https://github.com/saltstack-formulas/influxdb-formula/commit/13a55a7))


### Documentation

* **readme:** update readme and add some documentation ([d1fad82](https://github.com/saltstack-formulas/influxdb-formula/commit/d1fad82))


### Features

* **yamllint:** include for this repo and apply rules throughout ([f9e638c](https://github.com/saltstack-formulas/influxdb-formula/commit/f9e638c))


### Styles

* **misc:** fix coding style ([cece6c8](https://github.com/saltstack-formulas/influxdb-formula/commit/cece6c8))


### Tests

* **inspec:** use inspec to run tests ([34625cc](https://github.com/saltstack-formulas/influxdb-formula/commit/34625cc))
* **kitchen:** add binstub for Kitchen ([77791d1](https://github.com/saltstack-formulas/influxdb-formula/commit/77791d1))
* **kitchen:** fix InfluxDB version in test pillar (and pillar.example) ([59d23b3](https://github.com/saltstack-formulas/influxdb-formula/commit/59d23b3))
* **kitchen:** update Gemfile ([630d762](https://github.com/saltstack-formulas/influxdb-formula/commit/630d762))
* **kitchen:** update test pillar ([3af72f6](https://github.com/saltstack-formulas/influxdb-formula/commit/3af72f6))

0.0.2 / 2014-08-20
==================

 * Use default mapping on the main state

0.0.1 / 2014-08-20
==================

 * Initial release

<!--
 vi: set ft=markdown :
-->
