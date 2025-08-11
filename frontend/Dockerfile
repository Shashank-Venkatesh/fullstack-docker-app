# Use Node 14 alpine image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package.json & package-lock.json first for caching
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy rest of the frontend code
COPY . .

# Expose frontend port
EXPOSE 3000

# Start frontend
CMD ["npm", "start"]
