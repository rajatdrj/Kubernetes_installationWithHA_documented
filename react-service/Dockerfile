FROM node:21-alpine3.18 as builder
WORKDIR /app
COPY package*.json .
RUN npm i
COPY . .
RUN npm run build:prod


FROM nginx
WORKDIR /usr/share/nginx/html
ADD nginx.conf /etc/nginx/nginx.conf
RUN mkdir -p /usr/share/nginx/html/build
RUN rm -rf ./*
COPY --from=builder /app/build /usr/share/nginx/html/build/.
EXPOSE 80