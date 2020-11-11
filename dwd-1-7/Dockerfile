FROM ubuntu:16.04

RUN apt-get update -qq && apt-get install curl -y -qq >/dev/null
COPY script.sh .
RUN chmod +x script.sh
CMD ["./script.sh"]