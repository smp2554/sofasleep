# sofasleep

 winpty docker build --tag smp2554/ubuntu7 .
Sending build context to Docker daemon  324.6kB
Step 1/3 : FROM ubuntu
 ---> 74435f89ab78
Step 2/3 : RUN apt update
 ---> Using cache
 ---> 1aff087a320d
Step 3/3 : RUN apt install -y nginx
 ---> Using cache
 ---> d6a0d04c455c
Successfully built d6a0d04c455c
Successfully tagged smp2554/ubuntu7:latest
SECURITY WARNING: You are building a Docker image from Windows against a non-Win
dows Docker host. All files and directories added to build context will have '-r
wxr-xr-x' permissions. It is recommended to double check and reset permissions f
or sensitive files and directories.
