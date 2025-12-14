Best docker learning site

https://docker-curriculum.com/


Docker Client --- Docker.exe

Docker Engine --- Dockerd.exe [ Demon -- Background process ]

<img width="338" height="307" alt="Screenshot 2025-12-14 122459" src="https://github.com/user-attachments/assets/b5990590-78fe-441e-90d1-bdac07a2110f" />


Docker Container — From — Docker hub

# Run hello-world from docker hub
    $ docker run hello-world

namespaces and cgroups

Containers are platform independent

http://localhost:6901  [ Basic web server with port ]


Flags
-it [ interactive ]
-rm [ remove and start fresh ]
-d  [ Detached ]
-p  [ Map container port to host ]


-p 8080:80  [ Map container port 80 to host 8080 ]


# DockerFile for btop installation
    # User officila Alpine Linux image
    From Alpine: Latest

    # Install necessary package and btop
    RUN apk update && \
        apk add --no-cache bash curl git build-base ncurses-dev

    # Clone btop repository and build it
    RUN git clone https://github.com/aristocratos/btop.git /opt/btop && \
        cd /opt/btop && \
        make && \
        make install

    # Clean up
    RUN apk del git build-base ncurses-dev && rm -rf /var/cache/apk/* /opt/btop

    # Set the command to run btop
    CMD ["btop"]

# docker build and run image
    $ docker built -t btop-image .
    $ docker run -rm -it btop-image

# Commands
    $ docker pull busybox
    $ docker images
    $ docker run busybox
    $ docker run busybox echo "Hello from busybox"
    $ docker ps
    $ docker ps -a

    $ docker run --help
    $ docker rm [containerID] [containerID]
    $ docker rm $(docker ps -a -q -f status = existed)
        alternative command
    $ docker container prune
        alternative command
    $ docker rmi




