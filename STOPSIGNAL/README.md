### STOPSIGNAL

STOPSIGNAL is used to how to exit the container.
* By default docker request for exit and wait for some time.
lf it is not existing.it can force kill.
When your container received STOPSIGNAL your application can perform
 * you can close DB connections.
 * you can do some backup
