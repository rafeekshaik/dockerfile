FROM almalinux:9
RUN dnf install nginx -y
ADD https://raw.githubusercontent.com/rafeekshaik/docker/refs/heads/main/FROM/Dockerfile /tmp
CMD ["nginx", "-g","daemon off;"]
