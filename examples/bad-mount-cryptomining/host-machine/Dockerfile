FROM docker:19.03.15-dind

RUN set -ex \
    && apk add --no-cache \
    bash curl

COPY start-cron-and-dind.sh /usr/local/bin

ENTRYPOINT ["start-cron-and-dind.sh"]
CMD []


