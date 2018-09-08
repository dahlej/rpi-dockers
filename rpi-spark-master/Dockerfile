FROM dahlej/rpi-alpine-openjdk8
ADD https://archive.apache.org/dist/spark/spark-2.3.1/spark-2.3.1-bin-hadoop2.7.tgz /usr/local/
RUN cd /usr/local/ && tar xvfz spark-2.3.1-bin-hadoop2.7.tgz
EXPOSE 8080
EXPOSE 7077
RUN /usr/local/spark-2.3.1-bin-hadoop2.7/sbin/start-master.sh