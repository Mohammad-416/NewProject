FROM node:20-slim

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install
RUN npm install -D @tailwindcss/vite


COPY . .

CMD ["npm", "run", "dev", "--", "--host"]