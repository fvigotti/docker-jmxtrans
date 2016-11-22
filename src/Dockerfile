FROM java:8u45-jdk

MAINTAINER fvigotti

ENV version 250

ADD run-jmxtrans.sh /usr/bin/run-jmxtrans.sh
RUN chmod +x /usr/bin/run-jmxtrans.sh

# default json confs dir
VOLUME ["/var/lib/jmxtrans"]

# default logs dir
VOLUME ["/var/log/jmxtrans"]

CMD /usr/bin/run-jmxtrans.sh

