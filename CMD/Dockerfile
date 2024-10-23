FROM almalinux:9
RUN dnf install nginx -y
# FROM run:1.0  ---> we can use this instead of above two steps, since the run is already available as image in server
CMD ["nginx","-g","daemon off;"]
# since systemctl command will not work in containers & images we use the CMD command to start the nginx server as mentioned above.
