FROM node:18-alphine
WORKDIR /app
COPY . . 
RUN yarn install --production
CMD ["node", "src/index.js"]
EXPOSE 3000
