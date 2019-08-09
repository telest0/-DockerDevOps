docker run -it --name teamcity-server-instance  \
    -v /home/ubuntu/teamcity/data:/data/teamcity_server/datadir \
    -v /home/ubuntu/teamcity/logs:/opt/teamcity/logs  \
    -p 8080:8111 \
    jetbrains/teamcity-server
