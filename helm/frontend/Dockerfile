FROM node:16-slim
ENV NODE_ENV=development

WORKDIR /app
COPY package*.json ./
RUN npm install

COPY . .
ENV REACT_APP_BASE_URL=http://localhost:5000

EXPOSE 3000
CMD ["npm", "start"]
