FROM node:latest
WORKDIR /app
COPY package.json .
RUN npm install
RUN npm install -g @angular/cli
COPY . .
EXPOSE 4200		
CMD ["ng", "serve", "--port", "4200", "--host", "0.0.0.0"]
