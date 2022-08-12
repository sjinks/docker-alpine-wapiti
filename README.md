# docker-alpine-wapiti

**DEPRECATED, please use the [official Dockerfile](https://github.com/wapiti-scanner/wapiti/blob/master/Dockerfile).**

An Alpine-based image to run wapiti web application vulnerability scanner

## Usage

```bash
docker run -it --rm -v $(pwd)/wapiti:/.wapiti wildwildangel/wapiti --help
```

Mount points:
  * `/.wapiti`: this is where `wapiti` stores its progress and report files
