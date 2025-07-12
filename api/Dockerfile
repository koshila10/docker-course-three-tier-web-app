# Use a smaller image
FROM node:18-alpine

# Add non-root user
RUN addgroup -S appgroup && adduser -S appuser -G appgroup

WORKDIR /app

COPY . .

RUN npm install

# Use non-root user
USER appuser

CMD ["npm", "start"]

