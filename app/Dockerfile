FROM node18-alpine
WORKDIR usrsrcapp
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD [npm, start]