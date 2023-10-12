# Exercise 5: Analyse traffic in OpenSearch Dashboards

We'll now look at the results of the processing of the traffic you just generated in Opensearch Dashboards.

1. You should see a spike in traffic from the point where you generated it; or, search for the webserver IP address.
2. *Note* in the current build of this environment, zeek may not trigger the `file` or `http` analysis; otherwise you would also be able to see `zeek-file` and `zeek-http` types available with additional information - including the checksum of the file downloaded.
3. Use the magnifying glass to explore the record for one of the connections