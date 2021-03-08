# java-web-gradle-spring-websocket-vanilla

## Description
This is a gradle built springboot web app
using the STOMP subprotocol to communicate
over websockets to vanilla javascript clients.
By clients, we mean any number of visitors to
this website will see changes in real time.
  The project is simple, the visitor clicks a
button which is updated on the server as well as
a log. Any new visitor will receive all logs and
an updated click count.

## Tech stack
- java
- gradle
  - springboot
  - bootstrap
  - jquery
  - sockjs

## Docker stack
- gradle:jdk11

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
https://spring.io/guides/gs/messaging-stomp-websocket/
