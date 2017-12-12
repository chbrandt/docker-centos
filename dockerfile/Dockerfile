FROM centos:6

MAINTAINER "Carlos Brandt <carloshenriquebrandt at gmail>"

RUN yum -y install vim git tar wget curl which &&\
    yum clean all

RUN git clone -b master https://github.com/chbrandt/docker_commons.git && \
    ln -sf docker_commons/entrypoint.sh /.

ENTRYPOINT ["/entrypoint.sh"]
