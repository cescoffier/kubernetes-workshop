FROM registry.access.redhat.com/ubi8/ubi-minimal:8.3
# Run a command inside the container as we build.
# In this case, install java and jbang:
# Notice how we chain commands to avoid creating multiple intermediate layers
RUN microdnf install java-11-openjdk-devel unzip  \
  && curl -Ls "https://github.com/jbangdev/jbang/releases/download/v0.53.2/jbang-0.53.2.zip" --output jbang.zip \
  && unzip jbang.zip && rm jbang.zip && mv jbang-* jbang && chmod +x jbang/bin/jbang

COPY HelloWorld.java /root

# Set the default command to run when a new container is started with this image:
ENTRYPOINT jbang/bin/jbang /root/HelloWorld.java