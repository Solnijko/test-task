FROM ubuntu:24.04
RUN apt update && apt install -y openssh-server && rm -rf /var/lib/apt/lists/* && mkdir -p /run/sshd
EXPOSE 80 22
CMD ["/usr/sbin/sshd", "-D"]