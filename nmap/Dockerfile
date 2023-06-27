FROM andrewd/musl-cross
MAINTAINER Andrew Dunham <andrew@du.nham.ca>

# Add our build script
RUN mkdir -m 777 /build
ADD build.sh /build/build.sh

# This builds the program and copies it to /output
CMD /build/build.sh
