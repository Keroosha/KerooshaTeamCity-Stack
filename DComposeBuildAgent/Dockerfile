FROM jetbrains/teamcity-agent

RUN su -c "apt-get update \
 && apt-get install curl -y \
 && curl -L https://github.com/docker/compose/releases/download/1.19.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose\
 && chmod +x /usr/local/bin/docker-compose"