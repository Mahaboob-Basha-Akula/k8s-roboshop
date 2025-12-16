FROM almalinux:9
RUN dnf install telenet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD [ "sleep", "100000" ] 