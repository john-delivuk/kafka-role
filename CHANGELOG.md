# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and [Keep a changelog](https://github.com/olivierlacan/keep-a-changelog).

## [Unreleased](https://github.com/idealista/kafka-role/tree/develop)

## Fixed

- Set default value for Kafka Brokers to prevent error if not specified @john-delivuk

## Added

- Allow the setting of KAFKA_OPTS, useful for setting additional parameters and jmx_exporter.

## [1.7.0](https://github.com/idealista/kafka-role/tree/1.7.0) (2018-10-29)

## Fixed

- *[#40](https://github.com/idealista/kafka-role/issues/40) Avoided remove __consumer_offsets internal topic* @jmonterrubio

## Added

- *[#39](https://github.com/idealista/kafka-role/issues/39) Add extra configuration properties* @jmonterrubio

## [1.6.0](https://github.com/idealista/kafka-role/tree/1.6.0) (2018-10-09)

## Added

- *[#33](https://github.com/idealista/kafka-role/issues/33) Enable or disable GC log by configuration* @jmonterrubio
- *[#35](https://github.com/idealista/kafka-role/issues/35) Remove old kafka installation* @jmonterrubio
- *[#36](https://github.com/idealista/kafka-role/issues/36) Configure topics from role* @jmonterrubio

## Changed

- *[#34](https://github.com/idealista/kafka-role/issues/34) Use goss instead of testinfra for molecule test* @jmonterrubio

## [1.5.0](https://github.com/idealista/kafka-role/tree/1.5.0) (2018-06-06)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.4.0...1.5.0)

## Added

- *[#28](https://github.com/idealista/kafka-role/issues/28) Adding new variables to server.properties template* @amanzanotejon
- *[#30](https://github.com/idealista/kafka-role/issues/30) Kafka.service, log4j.properties and server.properties can be provided via playbooks* @jnogol

## [1.4.0](https://github.com/idealista/kafka-role/tree/1.4.0) (2018-06-06)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.3.1...1.4.0)

## Changed

- *[#20](https://github.com/idealista/kafka-role/issues/20) Update to kafka v1.1* @eskabetxe

## Fixed

- *[#26](https://github.com/idealista/kafka-role/issues/26) Testinfra tests don't pass under Vagrant* @eskabetxe

## [1.3.1](https://github.com/idealista/kafka-role/tree/1.3.1) (2018-02-27)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.3.0...1.3.1)

## Changed

- *[#23](https://github.com/idealista/kafka-role/issues/23) Using Vagrant hostmanager instead of Landrush* @dortegau

## Fixed

- *[#22](https://github.com/idealista/kafka-role/pull/22) Picking up Xms correctly from KAFKA_HEAP_OPTS environment variable* @didumgai

## [1.3.0](https://github.com/idealista/kafka-role/tree/1.3.0) (2018-02-01)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.2.0...1.3.0)

## Added

- *[#13](https://github.com/idealista/kafka-role/issues/13) Enable delete topics property* @jmonterrubio
- *[#12](https://github.com/idealista/kafka-role/issues/12) Enable auto create topics property* @jmonterrubio

## Changed

- *Use uvigo's mirror to download Kafka* @jnogol

- *[#16](https://github.com/idealista/kafka-role/pull/16) Remove Java role dependency* @maqdev

## Fixed

- *Fix Kafka errored version* @jnogol

- *[#16](https://github.com/idealista/kafka-role/pull/16) Create data path if not exists* @maqdev

## [1.2.0](https://github.com/idealista/kafka-role/tree/1.2.0) (2017-05-19)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.1.0...1.2.0)

## Changed

- *[#5](https://github.com/idealista/kafka-role/issues/5) Added kafka_hosts var to fix broker id issue* @jmonterrubio

## [1.1.0](https://github.com/idealista/kafka-role/tree/1.1.0) (2017-04-04)

## [Full Changelog](https://github.com/idealista/kafka-role/compare/1.0.0...1.1.0)

## Changed

- *[#2](https://github.com/idealista/kafka-role/issues/2) Change defaults vars and improve installation* @jmonterrubio

## [1.0.0](https://github.com/idealista/kafka-role/tree/1.0.0) (2017-02-28)

### Added

- *First release*
