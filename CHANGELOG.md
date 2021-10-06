# Changelog
All notable changes to this project will be documented in this file.


## [1.4.4] - 2020-06-15
### Added
 - SSLvserver metrics
 - New Label "citrixadc_server_name" for configured servicegroups under "services" stats.
 - Bug Fix for serial ADC connection 
 - Added package "iputils" in container image for debugging at runtime
 
## [1.4.5] - 2020-08-11
### Added
 - Python update : 2.7 to 3.8
 - New Label: "citrixadc_interface_id" for Interface metrics
 - Default LogLevel : INFO

### BugFixes:
 - Connection retries for ADC only on new Prometheus Requests.
 - Single Login Session.

## [1.4.6] - 2020-08-28
### Added
 - Ingress dashboard as per modifications in naming in CIC
 - Logging changes

### BugFixes:
 - Error handling modification


## [1.4.7] - 2021-02-08
### Added
 - Added adc_probe_success metric to indicate successful/Failed scrape
 - Added new metric "citrixadc_throughput_tx_mbits_rate"

## [1.4.8] - 2021-07-07
### Added
 - Added fix for lightweight-CPX not working with CME.
 - Updated pip requirements.

## [1.4.9] - 2021-10-05
### Added
 - Added fix to handle ERROR message for lbvs added by CIC.
