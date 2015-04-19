# Docker SABnzbd

Docker image for [SABnzbd](http://sabnzbd.org).

## Usage

```bash
docker run -d --name sabnzbd \
    -p 8080:8080 \
    -p 9090:9090 \
    -v <your-config-folder>:/config \
    -v <your-data-folder>:/data \
    fakewaffle/sabnzbd
```
