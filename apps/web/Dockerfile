FROM node:20-alpine
 
WORKDIR /usr/src/app
 
# Copy root package.json and lockfile
COPY package.json ./
 
RUN npm install
 
# Copy app source
COPY . .

