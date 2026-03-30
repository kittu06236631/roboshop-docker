FROM mongodb:1.0.0
# this creats /app and move there
WORKDIR /app
COPY packages.json .
COPY *.js .
RUN npm install
ENV MONGO="true" \
MONGO_URL="mongodb://<MONGODB-SERVER-IPADDRESS>:27017/catalogue"
RUN node server.js