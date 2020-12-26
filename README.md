# docker-alpine-wapiti

An Alpine-based image to run wapiti web application vulnerability scanner

## Usage

```bash
docker run -it --rm -v $(pwd)/wapiti:/.wapiti wildwildangel/wapiti --help
```

Mount points:
  * `/.wapiti`: this is where `wapiti` stores its progress and report files
