# dev_ElasticSearchRH7
Elastic Search Workspace and Development Notes

#### Elastic Stack Subsription Information - Free/OSS. | Platinum. | Enterprise
  - [Subscription Details](https://www.elastic.co/subscriptions) <br/>

#### Notes
- Ports for FW: 9200-9300
  - elasticsearch : 9200
  - logstash : 5044
  - kibana : 5601
  - beat : 5043
     
- ElasticSearch License Application for ESv2.3
  `$curl -XPUT -u <username> 'http://<hostname/ip>:9200/_license' -H "Content-Type: application/json" -d @/<path_to_license>/` <br/>
