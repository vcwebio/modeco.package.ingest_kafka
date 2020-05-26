# `package.ingest_ssl` - ModEco

The ModEco ingest SSL module package based on filebeat.  
See `conteco.docs.overview` for more information on the ModEco ecosystem.

This package is intended to be used for general purpose data ingestion.  
It is based on ElasticSearch Filebeat.

## Contents

The module consists of the following service stack:

 * `filebeat` - the ElasticSearch Filebeat data shipper.

## Configuration

At this moment filebeat.base, on which this package is based,
is configured to ship data into Kafka and ElasticSearch.
