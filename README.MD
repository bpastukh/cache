To run demo:

```docker build -t cache_demo . && docker run --rm -p 8080:80 -v $(pwd)/static:/usr/share/nginx/html/ --name cache_demo cache_demo```
