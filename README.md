Simple Vagrant box with an ELK stack for testing purposes:
* Elasticsearch
* Logstash collecting stats from:
  * collectd on CPU, memory, load and network stats on eth0
  * Nginx access and error logs
  * syslog ready
* Kibana   http://www.elasticsearch.org/overview/kibana/
   * Marvel ES monitoring  http://www.elasticsearch.org/overview/marvel/
   * HQ http://www.elastichq.org/
   * Elasticsearch Head  http://mobz.github.io/elasticsearch-head/
   * Big Desk  http://bigdesk.org/

To Get Started try one of the following:
  1. Send Syslog logs via TCP or UDP to the IP of this VM at port 5000.
  2. Place your log files into the data/syslog directory and Logstash will
      import any log file placed there.  
