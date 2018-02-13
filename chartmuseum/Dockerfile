FROM sles12/chartmuseum:0.2.1

RUN mkdir /sle-charts
COPY ./charts/portus-0.1.0.tgz /sle-charts 

ENTRYPOINT ["/usr/bin/chartmuseum", "--storage=local", "--storage-local-rootdir=/sle-charts"]
