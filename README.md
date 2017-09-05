# pcp
PCP

```
docker run -tid --privileged -p 9990:9990 -v /sys:/sys:ro -v /etc/localtime:/etc/localtime:ro -v /var/lib/docker:/var/lib/docker:ro -v /run:/run -v /var/log:/var/log -v /dev/log:/dev/log --name=pcp mariusmitrofan/pcp
```
