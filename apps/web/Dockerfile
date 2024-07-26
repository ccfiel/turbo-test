FROM node:20-alpine
 
WORKDIR /usr/src/app
 
# Copy root package.json and lockfile
COPY package.json ./
COPY package-lock.json ./
 
# Copy the api package.json
COPY apps/web/package.json ./apps/web/package.json
 
RUN npm install
 
# Copy app source
COPY . .