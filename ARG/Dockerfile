ARG version
FROM almalinux:${version:-8}
# we have to pass the some default version number/name and provide the required version number as the commandline argument like: version=9
#RUN cat /etc/*release  ---> to verify the OS version details
ARG Course=DevOps
ARG Trainer=PSPK
ENV Duration=90Hr
RUN echo "Course is:${Course}, Trainer is:${Trainer}, Duration is:${Duration}"
CMD [ "sleep","100" ]
