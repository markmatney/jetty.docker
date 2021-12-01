# Jetty on Alpine Linux

Build:

```bash
docker image build --tag jetty-alpine .
```

Run:

```bash
docker container run -it -p 8080:8080 jetty-alpine
```

To install the Jetty demo apps, apply the included patchfile before building the image:

```bash
git apply demo.patch
```