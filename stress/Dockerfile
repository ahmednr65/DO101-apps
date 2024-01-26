FROM registry.access.redhat.com/rhscl/httpd-24-rhel7

CMD ab -dSrk -c 20 -n 50000000 http://qod-web.quoteoftheday.svc.cluster.local:8080/random
