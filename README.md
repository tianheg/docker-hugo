# docker-hugo

```sh
docker run -d \
--name blog_live \
--restart always \
-v $(pwd):/src \
-p 1314:1313 \
-e HUGO_WATCH=true -e HUGO_BASEURL=http://127.0.0.1 \
tianheg/hugo:latest
```

## Acknowledgements

- [klakegg/docker-hugo](https://github.com/klakegg/docker-hugo)
- [jojomi/docker-hugo](https://github.com/jojomi/docker-hugo)
