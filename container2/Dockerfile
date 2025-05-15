FROM alpine 

WORKDIR /app

COPY . .

RUN chmod +x ./logger.sh
RUN mkdir -p /logs && touch /logs/database
CMD ["./logger.sh"]
