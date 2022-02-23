FROM node

WORKDIR /Courses/z2

COPY package.json /Courses/z2

RUN npm install

COPY . .

ENV PORT 8080

CMD ["node", "script.js"]
