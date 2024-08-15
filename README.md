# telegraf-kafka-influxdb

```bash
ORGANIZATION=IMT BUCKET=SmartCampusMaua KAFKA_BROKER=localhost:9094 KAFKA_TOPIC=IMT.SmartCampusMaua KAFKA_CONSUMER_GROUP=telegraf-kafka-influxdb-imt-lns INFLUXDB_URL=https://us-east-1-1.aws.cloud2.influxdata.com INFLUXDB_TOKEN=INFLUXDB_WRITE_TOKEN_HERE telegraf --config telegraf.conf
```