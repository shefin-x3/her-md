FROM quay.io/shefin/alexa:md
RUN git clone https://github.com/shefin-x3/her-md /root/Alexa/
WORKDIR /root/Alexa/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
