FROM rucio/rucio-dev:py3

# jguiang: install latest versions of gfal2 and davix
RUN yum install -y gfal2 davix

# jguiang: install SENSE-O v1.23
RUN python3 -m pip install sense-o-api==1.23
