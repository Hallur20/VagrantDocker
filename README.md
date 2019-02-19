# VagrantDocker

1. vagrant up

2. vagrant ssh

3. docker run --rm -v $(pwd)/data:/data/db --publish=27017:27017 --name dbms -d mongo

4. docker exec -it dbms bash
