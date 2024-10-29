FROM node:22


RUN apt update -y 
RUN apt install -y build-essential


WORKDIR /code
RUN node -v
RUN npm -v

COPY . .
RUN npm install
# ENTRYPOINT node -v

CMD ["npm", "run", "start"]