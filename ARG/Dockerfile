ARG version
FROM almalinux:${version:-8}
# we have to pass the some default version number/name and provide the required version number as the commandline argument like: version=9
#RUN cat /etc/*release  ---> to verify the OS version details
ARG Course=DevOps
ARG Trainer=PSPK

ARG Duration=90Hr
ENV Duration=${Duration}
#to access the ARG instruction into the runtime(container) we can create ENV with the same name as ARG and refer that.

RUN echo "Course is:${Course}, Trainer is:${Trainer}, Duration is:${Duration}"
CMD [ "sleep","100" ]
