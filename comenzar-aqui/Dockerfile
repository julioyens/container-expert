FROM alpine

# RUN, COPY, ADD , FROM

WORKDIR /app
# ADD vs COPY
COPY myapp.sh /app/

# Comandos de Linux (alpine)
RUN ls /app && chmod +x myapp.sh && apk add --update bash

CMD [ "./myapp.sh" ]
ENTRYPOINT [ "bash" ]

