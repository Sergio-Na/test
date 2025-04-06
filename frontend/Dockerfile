FROM node:16-slim

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Build for production or use development mode
# For production:
# RUN npm run build
# For development:
EXPOSE 3000
CMD ["npm", "start"]