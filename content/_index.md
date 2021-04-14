---
title: Introduction
type: docs
---

# Hours with Experts

## Kafka information

Kafka brokers

Windows

```
SET BOOTSTRAP_SERVERS=35.239.241.212:9092,35.239.230.132:9092,34.69.66.216:9092
windows/kafka-console-consumer.bat --bootstrap-server %BOOTSTRAP_SERVERS% --topic dehwe --from-beginning
```

Mac OS or Linux
```
export BOOTSTRAP_SERVERS=35.239.241.212:9092,35.239.230.132:9092,34.69.66.216:9092
bin/kafka-console-consumer.sh --bootstrap-server $BOOTSTRAP_SERVERS --topic dehwe --from-beginning
```

## HBase information

TODO
