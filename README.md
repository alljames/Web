# CLOUD NATIVE WALES: Web

## Join Us

We're in the process of starting up a Cloud Native community in Wales.

If you want to be a part of it please contact us via [twitter (Eng)](https://twitter.com/cloudnativewal), [twitter (Cym)](https://twitter.com/cloudnativecym) or [email](mailto:info@cloudnativewales.io).

If you have a passion to teach, share, help and/or learn then we're going to get along just fine!

## Docker

A Dockerfile has been added to the project to create a container:

```terminal
$ docker build -t cloudnativewales/web:1.0 .
```

Use the following command to run in debug mode allowing you to edit the code locally:

```terminal
$ docker run -d --name cloudnativewales.web -p 5000:80 -v "$(pwd)":/usr/share/nginx/html cloudnativewales/web:1.0
```