# LabVIEW Common Tools

## Platform

- CentOS 7
- LabVIEW 2018 SP1 64-bit Professional Version

## Needed Package

- JKI VI Package Manager 2017 (vipm)
- Caraya Unit Test Framework (installed by vipm)

## Details

1. **Logger**: Logger class to log the message.

## Log File

The log file is in the `log/` directory.
The test report will be in this directory.

## Run the Unit Tests

1. You can run the `testAll.vi` under the `tests/` directory in `common.lvproj` to run the unit tests by using the Caraya unit test framework.
2. Run the unit tests and generate a report as follows:

```bash
labview64 tests/testAllWithXmlReport.vi
```

This runs the tests using the Caraya unit test framework and generates report file: `log/testReport.xml`.
