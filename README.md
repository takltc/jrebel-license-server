# Jrebel License Server

A spring boot based Jrebel License Server.  

## Usage


```shell script
java -jar jrebel-license-server-2.0.0.jar 

# run daemond

nohup java -jar jrebel-license-server-2.0.0.jar >/dev/null 2>&1 &

# for docker users

sudo docker run -d --name jrebel-license-server -p 9090:9090 --restart always imjcker/jrebel-license-server:latest

```

[license]: https://www.apache.org/licenses/LICENSE-2.0

