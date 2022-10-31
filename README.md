# cors-anywhere
Express wrapper on Cors-anywhere proxy

## Build

```
git clone https://github.com/ilsrbn/cors-anywhere.git
cd cors-anywhere
docker build . -t www/cors-proxy
docker run -p 8080:8080 -d www/cors-proxy
```
