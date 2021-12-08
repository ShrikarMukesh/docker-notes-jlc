FROM openjdk:8
LABEL maintainer sri@jlcindia.com
RUN mkdir /home/myjlc
COPY Hai.java /home/myjlc
WORKDIR /home/myjlc
RUN javac Hai.java
CMD ["java", "Hai"]