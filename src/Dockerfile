FROM node:16.14.0-alpine3.14 AS base
RUN adduser -D nonroot
RUN apk add curl
WORKDIR /app
COPY package-lock.json package.json ./
RUN npm install
COPY --chown=nonroot:nonroot . .

FROM base AS prod
RUN npm run build
RUN chown -R nonroot:nonroot /app/node_modules/.cache

EXPOSE 8080
USER nonroot
CMD npm run start
