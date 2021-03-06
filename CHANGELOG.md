# Changelog

All notable changes to this project will be documented in this file.

## 0.9.0 - 2020-01-09

* 41: Introduce support for cluster-wide resources
* 36: Update last-applied-configuration annotation when patching a resource
* 18: Implement /v1/dryrun API

## 0.8.3 - 2020-12-22

* 33: Do not fail the whole patch when one ModRule fails
* 31: Enable patching non-existent arrays with -1

## 0.8.2 - 2020-12-21

* 29: Log missing JSONPath keys as DBG level messages

## 0.8.1 - 2020-12-18

* 27: Validation fails for ModRules without rejectMessage

## 0.8.0 - 2020-12-18

* 25: Introduce matchFor
* 23: Add message field to Reject rules
* 21: Implement Reject ModRules

## 0.7.1 - 2020-11-27

* 10: Implement a more forgiving add patch operation

## 0.7.0 - 2020-11-22

* 12: Add ability to construct patches based on select expression
* 8: Switch to nonroot certificate generation

## 0.6.0 - 2020-10-15

* 5: Document ModRule spec
* 3: Implement GitHub Actions CI

## 0.5.0 - 2020-10-07

* 1: Document KubeMod use cases

## 0.4.2 - 2020-10-07

Initial release
