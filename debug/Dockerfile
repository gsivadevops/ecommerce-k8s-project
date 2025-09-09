# installing telnet, curl to debug services
FROM almalinux:9
RUN dnf install telnet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD ["sleep","100000"]