
# ExtremeNetworks Integration for VOSS

This integration is for ExtremeNetworks products is created using the [elastic-package](https://github.com/elastic/elastic-package) tool. 
It includes the following datasets for receiving logs over syslog or read from a file:

- `VOSS` dataset: supports ExtremeNetworks from VOSS Exporter in the Syslog format.

## Compatibility

## Logs

### VOSS

The `VOSS` dataset collects the VOSS logs. The VOSS devices are able to send only on UDP Ports 514-530

An example event for `VOSS` looks as following:


Consider using the README template file `_dev/build/docs/README.md`to generate a list of exported fields or include a sample event.