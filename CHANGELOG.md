# Changelog

All notable changes to `soap-client-bundle` will be documented in this file.

Updates should follow the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

- 1.4.0
  introduced getOptions method to retrieve all SoapClient options (default + custom)
  fixed null handling in ResponseEvent & pre- and postCall
- 1.3.0
  introduced interface for SoapClient
  upgrade phpunit to v7
- 1.2.0
  introduced enable_profiler config option to improve prod settings
- 1.1.0
  introduced the possibility to add callables as Mock detectors.
  Made addRequest, addResponse public therefor.
