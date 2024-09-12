FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/rmjmadu/WHITEALFHA_MD /root/rmjmadu
WORKDIR /root/rmjmadu/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
