FROM wxwmatt/hadoop-base:2.1.1-hadoop3.3.1-java8

HEALTHCHECK CMD curl -f http://localhost:8042/ || exit 1

ADD run.sh /run.sh
RUN chmod a+x /run.sh

EXPOSE 8042

CMD ["/run.sh"]
