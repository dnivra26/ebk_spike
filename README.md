Docker compose to try out filebeat modules with elasticsearch and kibana

## Useful commands
1. List all plugins  
`http://localhost:9200/_cat/plugins?v&s=component&h=name,component,version,description`
2. Check cluster health  
`http://localhost:9200/_cluster/health?pretty`
3. Search an index
`http://localhost:9200/filebeat-6.2.4-2018.05.19/_search?q=%22apache2%22`