FROM python:3.9.18-alpine3.19

RUN apk add build-base libxml2-dev libxslt-dev libffi-dev tzdata \
    && pip install parsedmarc msgraph-core==0.2.2

COPY parsedmarc.ini /
COPY credentials.json /
COPY token.json /

#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
