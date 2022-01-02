FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/whitesr09/white_sr/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/whitesr09/uploads
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
