FROM    node:9-alpine
ADD     https://raw.githubusercontent.com/fjodoin-pklabs/public/main/scenario-1/package.json /
ADD     https://raw.githubusercontent.com/fjodoin-pklabs/public/main/scenario-1/server.js /
ENV     APP_ID="$spn3_application_id"
ENV 	APP_KEY="$spn3_client_secret"
ENV	TENANT_ID="$tenantId"
RUN     npm install
EXPOSE  80
CMD     ["node", "server.js"]
