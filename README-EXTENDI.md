Add this line to vars file, otherwise solr will not work in distribuited mode:

    solr_cores: ""

And zoopeer_nodes ('ip': 'id') in this format:

    zookeeper_nodes: {
                       '192.168.0.1': '1',
                       '192.168.0.2': '2',
                       '192.168.0.3': '3',
                     }
