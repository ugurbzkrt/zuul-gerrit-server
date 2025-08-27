Of File: https://opendev.org/zuul/zuul/src/branch/master/doc/source/examples/docker-compose.yaml

```
cd /opt

git clone https://opendev.org/zuul/zuul

cd zuul/doc/source/examples

sudo -E docker-compose -p zuul-tutorial up -d

sudo -E docker-compose -p zuul-tutorial down
```

Query:

```
git clone "http://Your-IP/zuul-config" && (cd "zuul-config" && mkdir -p git rev-parse --git-dir/hooks/ && curl -Lo git rev-parse --git-dir/hooks/commit-msg http://Your-IP/tools/hooks/commit-msg && chmod +x git rev-parse --git-dir/hooks/commit-msg) 
```
