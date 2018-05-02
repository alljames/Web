# CLOUD NATIVE WALES :octocat: BRODORION Y CWMWL CYMRU

## Join Us || Ymunwch â ni

We're in the process of starting up a Cloud Native community in Wales.

*Rydym ni wrthi'n sefydlu cymuned 'Cloud Native' yng Nghymru.*

If you want to be a part of it please contact us via [twitter](https://twitter.com/cloudnativewal) [email](mailto:info@cloudnativewales.io).

*Os hoffech chi ymuno â ni mae croeso i chi gael gafael arnom ni drwy [twitter](https://twitter.com/cloudnativewal) [ebost](mailto:info@cloudnativewales.io).*

If you have a passion to teach, share, help and/or learn then we're going to get along just fine!

*Os ydych chi'n frwdfrydig am ddysgu, addysgu, rhannu eich gwybodaeth neu i gynnig cymorth byddwn ni'n hapus i glywed o chi!*

## Docker

A Dockerfile has been added to the project to create a container:

```terminal
$ docker build -t cloudnativewales/web:1.0 .
```

Use the following command to run in debug mode allowing you to edit the code locally:

```terminal
$ docker run -d --name cloudnativewales.web -p 5000:80 -v "$(pwd)":/usr/share/nginx/html cloudnativewales/web:1.0
```