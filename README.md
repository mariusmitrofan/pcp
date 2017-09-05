PCP container with:
- pmcd
- pmie
- pmlogger
- pmproxy
- pmwebd

```
docker run -tid \
--privileged \
-p 9990:9990 \
    -v /var/lib/docker:/var/lib/docker:ro -v \
    -v /sys:/sys:ro \
    -v /var/run:/var/run \
    -v /rootfs:/rootfs:ro \
    -v /cgroup:/cgroup:ro \
    -v /etc/localtime:/etc/localtime:ro \
--name=pcp \
mmitrofan/pcp:latest
```
