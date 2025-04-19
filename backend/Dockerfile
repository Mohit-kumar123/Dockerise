FROM node:20-slim@sha256:abc123...  

WORKDIR /app

# Install backend dependencies
COPY package*.json ./
RUN npm install

# Copy backend source code
COPY . .

EXPOSE 5001

CMD ["npm", "start"]