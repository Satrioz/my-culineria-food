FROM mhart/alpine-node:12

WORKDIR /src

COPY . .

RUN npm install
RUN npm prune --production

EXPOSE 3000

CMD ["npm", "start"]