<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">EFK stack log management</h3>

  <p align="center">
    Using Elasticsearch, fluentd and Kibana to retrieve and dispaly jboss logs
  </p>
</p>



<!-- ABOUT THE PROJECT -->
## About The Project

EFK stack is used to retrieve and display several types of logs to users. This project mainly focus on reading jboss logs.

<!-- GETTING STARTED -->
## Getting Started

To get up and runing the project follow the following steps.

### Prerequisites

Docker needs to installed in your system

### Sreps

1. Replace the <log_file_location> in docker-compose.yml file and Dockerfile.
2. docker-compoase up -d
3. Navigate http://localhost:5601 to access the Kibana UI from the browser
4. Create index and index pattern to discover the logs from the Kibana UI

   
