FROM bitnami/node:9

RUN mkdir -p /usr/src/k8s_node_app

WORKDIR /usr/src/k8s_node_app

ADD index.js ./

ADD package.json ./

RUN npm install

CMD ["npm", "start"]
