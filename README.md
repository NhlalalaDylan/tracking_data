## Setup
- Create directory data_input/incoming and data_input/archive
  - Drop files in data_input/incoming. files will be archived in data_input/archive
- Run : docker-compose up -d
- run NiFi on https://localhost:8443/nifi/
- run Kafka Control-center on http://localhost:9021/clusters
- run Apache Druid console on http://localhost:8888/ 
- Architecture is in the about directory 
- Flow definition file with external services: mi-c3_etl.json



