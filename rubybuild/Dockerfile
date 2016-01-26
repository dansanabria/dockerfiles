# image for rspec testing purposes
FROM centos:centos6
RUN yum install -y git rpm-build curl which tar sudo
RUN gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
RUN curl -sSL https://get.rvm.io | bash -s stable
RUN /bin/bash -c 'source /etc/profile.d/rvm.sh; rvm install 2.0.0-p451; gem install bundler -v 1.10.6'

