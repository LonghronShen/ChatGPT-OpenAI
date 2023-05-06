FROM node:14

WORKDIR /app

COPY . .

RUN npm install --save-dev -ddd

ENV OPENAI_API_KEY=

EXPOSE 5000

ENTRYPOINT ["npm", "run", "server"]
