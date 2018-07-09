# pyredis
Simple Python and Redis implementation


Start Docker or use a public play-with-docker https://labs.play-with-docker.com


    [node1] (local) root@192.168.0.58 ~
    $ git clone https://github.com/zysm/pyredis.git

change directory to `pyredis` and run `docker-compose`
    
    $ cd pyredis
    $ docker-compose up -d

Open up http://ip172-18-0-29-bd1fv6ts2ti0008c7b2g-5000.direct.labs.play-with-docker.com/ 


To stop your services once you’ve finished with them:

    $ docker-compose stop

You can bring everything down, removing the containers entirely, with the down command. Pass --volumes to also remove the data volume used by the Redis container:

    $ docker-compose down --volumes
