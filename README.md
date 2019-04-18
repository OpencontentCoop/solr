# Solr

![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/Opencontent/solr.svg?style=popout-square)



## Local Build & run

    docker build -t solr:4.10.4 .
    docker run -eVERBOSE=yes -it --rm -P solr -V -a '-XX:+UnlockExperimentalVMOptions -XX:+UseCGroupMemoryLimitForHeap' 

Please note, java8 has a bad support for memory restrictions 

"-XX:+UnlockExperimentalVMOptions -XX:+UseCGroupMemoryLimitForHeap" multicore

~                                                                                                                                                    
