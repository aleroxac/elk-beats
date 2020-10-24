## filebeat
    ### configs
    - [] processors
    - [] keystore
    - [] multiline
    - [] json
    - [] type
    - [] tags
    - [] fields
    - [] exclude lines
    - [] include lines
    - [] ignore_older
    - [] harvester_buffer_sizeedit
    - [] max_bytes 
    - [] scan_frequency
    - [] scan.sort
    - [] scan.order
    - [] configure paths
    - [] filebeat.registry
    - [] filebeat.config.inputs
    - [] filebeat.config.modules
    - [] filebeat.modules
    - [] live reloading
    - [] ilm
    - [] index template
    - [] kibana dashboards
    ### inputs
    - [] file
    - [] docker
    - [] s3
    - [] csv / xlsx
    ### outputs
        #### file
        - [] path
        - [] filename
        - [] rotate_every_kb
        - [] number_of_files
        - [] permissions
        #### elasticsearch
        - [] pipeline / ingest-node
        - [] compression level
        - [] worker
        - [] index template
        - [] mappings
        - [] max_retries
        - [] bulk_max_size
        - [] backoff.init
        - [] backoff.max
        - [] timeout
        #### logstash
        - [] compression level
        - [] worker
        - [] loadbalance
        - [] pipelining
        - [] ttl
        - [] max_retries
        - [] bulk_max_size
        - [] timeout
        - [] backoff.init
        - [] backoff.max



## metricbeat
    ### modules
    - [] elasticsearch
    - [] logstash
    - [] kibana
    - [] beats

    - [] http
    - [] apache
    - [] nginx

    - [] docker
    - [] kubernetes

    - [] postgresql
    - [] mongodb
    - [] sql

    - [] redis
    - [] rabbitmq

    - [] aws
    - [] system



## packetbeat
- [] http
- [] https
- [] tls
- [] tcp
- [] udp
## auditbeat
## heartbeat



setup.template.settings:
    index.number_of_shards: 1



