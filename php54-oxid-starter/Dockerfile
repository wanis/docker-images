FROM nfqlt/php54-dev

CMD exec bash -lc 'run-parts /etc/rc.d && exec /usr/sbin/sshd -De'

ADD build /build
RUN bash /build/setup_docker.sh && rm -Rf /build

