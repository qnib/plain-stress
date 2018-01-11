# plain-stress
Docker image holding the tool stress to generate load


```
$ docker run -ti --rm --cpuset-cpus 0  --cpu-shares 100 qnib/plain-stress nice -n 19 stress -c 2
[II] qnib/init-plain script v0.4.28
> execute CMD 'stress -c 2'
stress: info: [1] dispatching hogs: 2 cpu, 0 io, 0 vm, 0 hdd
```
