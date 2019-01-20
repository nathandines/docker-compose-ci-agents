FROM python:3.7-alpine

RUN apk add --no-cache build-base libffi-dev openssl-dev

RUN pip3 install --no-cache-dir 'ansible>=2,<3'

ENTRYPOINT ["ansible"]
