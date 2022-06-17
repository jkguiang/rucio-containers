FROM rucio/rucio-dev:py3

RUN sed -i "1s/.*/#!\/usr\/bin\/python2/" /usr/bin/yum
RUN sed -i "1s/.*/#!\/usr\/bin\/python2/" /usr/libexec/urlgrabber-ext-down

RUN yum install -y gfal2 davix

RUN python3 -m pip install sense-o-api==1.23
