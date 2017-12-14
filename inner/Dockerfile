FROM busybox:glibc
COPY bin/ /usr/local/bin/
COPY lib/ /usr/local/lib/
ENV LD_LIBRARY_PATH /usr/local/lib
CMD ["/usr/local/bin/hello"]
