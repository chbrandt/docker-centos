FROM centos:6

MAINTAINER "Carlos Brandt <carloshenriquebrandt at gmail>"

RUN git clone https://github.com/chbrandt/docker_commons.git && \
    ln -sf docker_commons/entrypoint.sh /.

ENTRYPOINT ["/entrypoint.sh"]
