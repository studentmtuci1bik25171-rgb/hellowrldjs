# 1.15
Dockerfile:
FROM node:14-alpine
COPY . .
CMD ["node", "hello.js"]
