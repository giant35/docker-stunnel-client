# docker-stunnel-client


##运行
```
git clone https://github.com/giant35/docker-stunnel-client.git
#修改 docker-stunnel-client/stunnel.conf connect = stunnelserver:6080
docker build -t stunnel:client docker-stunnel-client
docker run -d -p 1080:1080 stunnel:client
```
