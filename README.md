# ELK-Networking
This repository contains different configurations for logstash, elasticsearch and kibana.

# Logstash
Configuration files directory: /etc/logstash/conf.d/

# Elasticsearch 
Templates: 

Just paste entire text files into your development console in Kibana.

Or execute this on your elasticsearch server:

curl -XPUT localhost:9200/_template/name -d '
{
content
}
'
# Kibana

Visualizations (import json on kibana -> Management -> Saved objects)

Dashboards (import json on kibana -> Management -> Saved objects)
  
