FROM node:10

# Change working directory
WORKDIR "/app"

ENV NODE_ENV production
ENV PORT 3001

# Update packages and install dependency packages for services
RUN apt-get update \
 && apt-get dist-upgrade -y \
 && apt-get clean \
 && echo 'Finished installing dependencies'

# Install npm production package
#COPY package.json /app
#RUN npm i
#COPY . /app/
#RUN npm run build

#CMD npm start

CMD npm run dev

#CMD export PORT=3001 && npm start

