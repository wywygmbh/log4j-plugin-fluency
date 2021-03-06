# Changelog

## 1.3.2

### Fixes

* handle log4j 2.6 signature change - thanks [@askannon](https://github.com/askannon)

## 1.3.1

### Fixes

* fix log messages with exceptions - they were dropped and only the message got logged

## 1.3.0

### Features

* [[#2](https://github.com/wywygmbh/log4j-plugin-fluency/pull/2)] add support for fluency configuration options - thanks [@takumakanari](https://github.com/takumakanari)

## 1.2.0

### Features

* [[#1](https://github.com/wywygmbh/log4j-plugin-fluency/pull/1)] add support for PatternLayout - thanks [@takumakanari](https://github.com/takumakanari)

## 1.1.1
* switch to `StatusLogger` for internal logging

## 1.1.0
* add generic `<StaticField>` configuration
    * deprecates `application=""` attribute (it still works, but please migrate)

## 1.0.0
* switch groupId for maven central registration

## 0.1.0
* initial release
