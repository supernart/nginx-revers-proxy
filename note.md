# setup
1. run install.sh at server
2. copy >> nginx.conf, docker-compose.yml to Server [path ~]
3. run docker-compose up -d --force-recreate

# For AWS
4. set security group (CDN) at EC2 >> port 8080, ip: x.x.x.x/32
