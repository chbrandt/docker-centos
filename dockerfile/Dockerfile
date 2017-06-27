FROM centos:6

MAINTAINER "Carlos Brandt <carloshenriquebrandt at gmail>"

RUN yum -y groupinstall "Development Tools"     &&\
    yum -y install  ncurses-devel libXt-devel \
                    gcc gcc-c++ gcc-gfortran  \
                    compat-gcc-34-g77         \
                    perl-ExtUtils-MakeMaker   \
                    python-devel              \
                    libpng-devel              \
                    vim tar wget which git curl &&\
    yum clean all

