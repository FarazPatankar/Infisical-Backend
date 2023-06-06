FROM nginx:alpine

ARG PORT
ENV PORT=$PORT

RUN echo "$RAILWAY_SERVICE_{API}_URL"
RUN echo "$RAILWAY_SERVICE_API_URL"
RUN printenv

COPY ./nginx.conf /etc/nginx/nginx.conf

CMD ["printenv"]
