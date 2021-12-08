---
title: influx replication list
description: Manage replication connections for replicating data
menu:
  influxdb_2_1_ref:
    name: influx replication list
    parent: influx replication
weight: 102
influxdb/v2.1/tags: [write]
related:
  - /influxdb/v2.1/reference/cli/influx/replication
---

NAME:
   influx replication list - List all replication streams and corresponding metrics

USAGE:
   influx replication list [command options] [arguments...]

OPTIONS:
   --name value, -n value  Filter results to only replication streams with a specific name
   --org-id value          Local org ID [$INFLUX_ORG_ID]
   --org value, -o value   Local org name [$INFLUX_ORG]
   --remote-id value       Filter results to only replication streams for a specific remote connection
   --local-bucket value    Filter results to only replication streams for a specific local bucket

<!--
   COMMON OPTIONS:
   --host value                     HTTP address of InfluxDB [$INFLUX_HOST]
   --skip-verify                    Skip TLS certificate chain and host name verification [$INFLUX_SKIP_VERIFY]
   --configs-path value             Path to the influx CLI configurations [$INFLUX_CONFIGS_PATH]
   --active-config value, -c value  Config name to use for command [$INFLUX_ACTIVE_CONFIG]
   --http-debug
   --json                           Output data as JSON [$INFLUX_OUTPUT_JSON]
   --hide-headers                   Hide the table headers in output data [$INFLUX_HIDE_HEADERS]
   --token value, -t value          Token to authenticate request [$INFLUX_TOKEN]
-->