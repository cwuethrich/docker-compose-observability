# docker-compose-observability

Verschiedene Docker Compose Dateien zur Replikation von Observability Daten.

| Ordner                   | Beschreibung                                                                                            |
| ------------------------ | ------------------------------------------------------------------------------------------------------- |
| elastic\-log\-sample     | Replikation eines Elasticsearch Indexes mit Hilfe von Logstash\.                                        |
| elastic\-simple          | Zentrale Plattform aufgrund von Elastic Stack\. Besteht aus Kibana und drei Elastic Search Nodes\.      |
| elastic\-single          | Zentrale Plattform aufgrund von Elastic Stack\. Besteht aus Kibana und einem Elastic Search Node\.      |
| kafka\-connect\-debezium | Repliziert Daten ab Microsoft SQL Server nach Apache Kafka\. Der SQL Server ist dabei nicht enthalten\. |
| kafka\-edge              | Apache Kafka Infrastruktur für die Replikation ab oder nach Kafka\.                                     |
| logstash\-kafka          | Replikation von Metriken ab Apache Kafka\.                                                              |
| logstash\-mssql          | Replikation von Logeinträgen ab Microsoft SQL Server\. Der SQL Server ist dabei nicht enthalten\.       |
| logstash\-spblitz        | Replikation von Daten, welche über das SQL Server First Responer Kit gesammelt werden\.                 |
