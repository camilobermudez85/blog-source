FROM ubuntu

ADD memory-sink /memory-sink
RUN apt-get -y update; apt-get -y install stress cgroup-tools;

CMD ["/memory-sink"]
