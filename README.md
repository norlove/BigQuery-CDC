# BigQuery-CDC
This repo contains an example of how to stream UPSERTs natively into BigQuery.

BigQuery change data capture (CDC) updates your BigQuery tables by processing and applying streamed updates to existing data. This synchronization is accomplished through upsert and delete row operations, which are streamed in real-time by the BigQuery Storage Write API. 

Documentation on how to use the Storage Write API can be found [HERE](https://cloud.google.com/bigquery/docs/write-api).

The blog post which provides context into BigQuery CDC and streaming upserts can be found [HERE - Add when available](https://google.com).

Please refer and copy the files from the *cdc-example* folder.
