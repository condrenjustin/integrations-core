# CHANGELOG - mcache

## 1.10.0 / 2020-05-17 / Agent 7.20.0

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.9.1 / 2020-04-04 / Agent 7.19.0

* [Fixed] Remove logs sourcecategory. See [#6121](https://github.com/DataDog/integrations-core/pull/6121).

## 1.9.0 / 2020-01-13 / Agent 7.17.0

* [Added] Use lazy logging format. See [#5377](https://github.com/DataDog/integrations-core/pull/5377).

## 1.8.0 / 2019-12-02 / Agent 7.16.0

* [Added] Add version metadata. See [#4935](https://github.com/DataDog/integrations-core/pull/4935).

## 1.7.0 / 2019-10-29

* [Added] Add log section in the example configuration file. See [#4885](https://github.com/DataDog/integrations-core/pull/4885).

## 1.6.0 / 2019-05-14 / Agent 6.12.0

* [Added] Adhere to code style. See [#3537](https://github.com/DataDog/integrations-core/pull/3537).

## 1.5.0 / 2019-02-18 / Agent 6.10.0

* [Added] Finish Python 3 support. See [#2915](https://github.com/DataDog/integrations-core/pull/2915).

## 1.4.0 / 2019-01-04 / Agent 6.9.0

* [Added] Support Python 3. See [#2783][1].

## 1.3.2 / 2018-09-04 / Agent 6.5.0

* [Fixed] Add data files to the wheel package. See [#1727][2].

## 1.3.1 / 2018-06-20 / Agent 6.4.0

* [Fixed] Fix connection to unix socket for new binary. See [#1755][3].

## 1.3.0 / 2018-06-07

* [Added] Package `auto_conf.yaml` for appropriate integrations. See [#1664][4].
* [FEATURE] Add support for SASL authentication.

## 1.2.0 / 2018-05-11

* [FEATURE] Add custom tag support for service check.
* [FEATURE] Hardcode the 11211 port in the Autodiscovery template. See [#1444][5] for more information.

## 1.1.0 / 2017-11-21

* [UPDATE] Update auto_conf template to support agent 6 and 5.20+. See [#860][6]

## 1.0.0 / 2017-03-22

* [FEATURE] adds mcache integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2783
[2]: https://github.com/DataDog/integrations-core/pull/1727
[3]: https://github.com/DataDog/integrations-core/pull/1755
[4]: https://github.com/DataDog/integrations-core/pull/1664
[5]: 
[6]: https://github.com/DataDog/integrations-core/issues/860