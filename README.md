# Mastering Kafka consumer distribution 
## A guide to efficient scaling and resource optimization

### Key KIPs:

1. [KIP-848: The Next Generation of the Consumer Rebalance Protocol](https://cwiki.apache.org/confluence/display/KAFKA/KIP-848%3A+The+Next+Generation+of+the+Consumer+Rebalance+Protocol)
2. [KIP-429: Kafka Consumer Incremental Rebalance Protocol](https://cwiki.apache.org/confluence/display/KAFKA/KIP-429%3A+Kafka+Consumer+Incremental+Rebalance+Protocol)


### Useful KIPs

1. [KIP-999: Server-side Consumer Lag Metrics](https://cwiki.apache.org/confluence/display/KAFKA/KIP-999%3A+Server-side+Consumer+Lag+Metrics)
2. [KIP-814: Static membership protocol should let the leader skip assignment](https://cwiki.apache.org/confluence/display/KAFKA/KIP-814%3A+Static+membership+protocol+should+let+the+leader+skip+assignment)
3. [KIP-759: Unneeded repartition canceling](https://cwiki.apache.org/confluence/display/KAFKA/KIP-759%3A+Unneeded+repartition+canceling)
4. [KIP-1000: List Client Metrics Configuration Resources](https://cwiki.apache.org/confluence/display/KAFKA/KIP-1000%3A+List+Client+Metrics+Configuration+Resources)
5. [KIP-945: Update threading model for Consumer](https://cwiki.apache.org/confluence/display/KAFKA/KIP-945%3A+Update+threading+model+for+Consumer)
6. [KIP-915: Txn and Group Coordinator Downgrade Foundation](https://cwiki.apache.org/confluence/display/KAFKA/KIP-915%3A+Txn+and+Group+Coordinator+Downgrade+Foundation)
7. [KIP-899: Allow producer and consumer clients to rebootstrap](https://cwiki.apache.org/confluence/display/KAFKA/KIP-899%3A+Allow+producer+and+consumer+clients+to+rebootstrap)
8. [KIP-860: Add client-provided option to guard against replication factor change during partition reassignments](https://cwiki.apache.org/confluence/display/KAFKA/KIP-860%3A+Add+client-provided+option+to+guard+against+replication+factor+change+during+partition+reassignments)
9. [KIP-881: Rack-aware Partition Assignment for Kafka Consumers](https://cwiki.apache.org/confluence/display/KAFKA/KIP-881%3A+Rack-aware+Partition+Assignment+for+Kafka+Consumers)
10. [KIP-851: Add requireStable flag into ListConsumerGroupOffsetsOptions](https://cwiki.apache.org/confluence/display/KAFKA/KIP-851%3A+Add+requireStable+flag+into+ListConsumerGroupOffsetsOptions)
11. [KIP-811: Add config repartition.purge.interval.ms to Kafka Streams](https://cwiki.apache.org/confluence/display/KAFKA/KIP-811%3A+Add+config+repartition.purge.interval.ms+to+Kafka+Streams)
12. [KIP-792: Add "generation" field into consumer protocol](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=191336614)
13. [KIP-735: Increase default consumer session timeout](https://cwiki.apache.org/confluence/display/KAFKA/KIP-735%3A+Increase+default+consumer+session+timeout)
14. [KIP-699: Update FindCoordinator to resolve multiple Coordinators at a time](https://cwiki.apache.org/confluence/display/KAFKA/KIP-699%3A+Update+FindCoordinator+to+resolve+multiple+Coordinators+at+a+time)

### Scaling - metrics and tools
1. [Keda for Apache Kafka](https://keda.sh/docs/2.13/scalers/apache-kafka/)
2. [Knative metrics](https://knative.dev/docs/serving/autoscaling/autoscaling-metrics/)
3. [Knative Source for Apache Kafka](https://knative.dev/docs/eventing/sources/kafka-source/)
4. [Kafka Consumers Scheduling and Scaling](https://docs.google.com/document/d/1UktwiDyqq07MtA7pUlahEpux5CCdAsyI6k3nkQeeqXw/edit#heading=h.n8a530nnrb)
5. [Seglo - Kafka Lag Exporter GitHub](https://github.com/seglo/kafka-lag-exporter)
6. [Seglo - Lag Expoerter Description](https://www.lightbend.com/blog/monitor-kafka-consumer-group-latency-with-kafka-lag-exporter)
7. [Aiven lag predictor (docs)](https://aiven.io/docs/products/kafka/concepts/consumer-lag-predictor) 
8. [Burrow](https://github.com/linkedin/Burrow)


### Other useful materials by Olena Kutsenko and Olena Babenko
1. [Kafka Summit London 2023: The Dark and Dirty Side of Fixing Uneven Partitions](https://www.confluent.io/events/kafka-summit-london-2023/the-dark-and-dirty-side-of-fixing-uneven-partitions/)
2. [Prevent uneven distribution of data across Apache Kafka® partitions - Olena Babenko](https://www.youtube.com/watch?v=tQMfXmzBnaQ)
3. [Ways to balance your data across Apache Kafka® partitions](https://aiven.io/developer/balance-data-across-kafka-partitions)
4. [A guide to Apache Kafka® tiered storage with Aiven and Terraform](https://aiven.io/developer/kafka-tiered-storage-terraform)
5. [First steps with the Apache Kafka® Java client library](https://aiven.io/developer/first-steps-kafka-java-client-library)
6. [Stream Mastodon data to Apache Kafka® using NodeJS and TypeScript](https://aiven.io/developer/mastodon-kafka-js)
7. [Connecting Apache Kafka® and Aiven for ClickHouse®](https://aiven.io/developer/connecting-kafka-and-clickhouse)


### Aiven for Apache Kafka
**Register your Aiven for Apache Kafka service with extra credits at [Aiven](https://go.aiven.io/olena-sign-up).**

### Follow more updates and articles from us on

LinkedIn: 
- [https://www.linkedin.com/in/olenakutsenko/](https://www.linkedin.com/in/olenakutsenko/)
- [https://www.linkedin.com/in/melhelen/](https://www.linkedin.com/in/melhelen/)

Twitter:
- [https://twitter.com/OlenaKutsenko](https://twitter.com/OlenaKutsenko)


