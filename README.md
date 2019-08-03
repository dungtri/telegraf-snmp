# Telegraf Docker Image with Net-SNMP

[![Build Status](https://drone.dungtri.be/api/badges/dungtri/telegraf-snmp/status.svg)](https://drone.dungtri.be/dungtri/telegraf-snmp)

Telegraf is an agent for collecting metrics and writing them to InfluxDB or other outputs. The reason why I created this repository ([Docker Hub link](https://hub.docker.com/r/nuntz/telegraf-snmp/)) is that the official one does not include the SNMP MIBs, used by the `input.snmp` input plugin.

Based on:

* https://github.com/influxdata/influxdata-docker
* https://github.com/weldpua2008/docker-net-snmp
