# jupyter-codeserver

this is note of set up my matapad10.4 for fun.

```
git clone https://github.com/xianglishan/jupyter-codeserver.git
```

if you use password for code-server, please edit PASSWORD in dockercompose.yml

to run docker as deamon

```
docker-compose up -d --build
```


code-server
---

code-server:http://{ip address}:8080/

![Imgur](https://i.imgur.com/Hg2VLon.jpg)


jupyterLb
---

use ssh port forward

```
ssh -i {public key} -L 8888:localhost:8888 {username}@{ip address}
```

jupyterLab :http://127.0.0.1{or localhost}:8888/

![Imgur](https://i.imgur.com/hdztqCU.jpg)


host files "work" are mounted
