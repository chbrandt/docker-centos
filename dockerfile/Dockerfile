FROM chbrandt/centos:base

RUN yum -y groupinstall "Development Tools"   &&\
    yum -y install  ncurses-devel libXt-devel \
                    gcc gcc-c++ gcc-gfortran  \
                    compat-gcc-34-g77         \
                    perl-ExtUtils-MakeMaker   \
                    python-devel              \
                    libpng-devel              &&\
    yum clean all
