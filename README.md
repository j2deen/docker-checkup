# This will install lighttpd and checkup in a container.

```
# get docker compose and config
git clone https://github.com/j2deen/docker-checkup.git checkup
cd checkup

# use sample configuration
cp config/config.sample.js config/config.js
cp config/checkup.sample.json config/checkup.json

# create and start
docker-compose up
```
