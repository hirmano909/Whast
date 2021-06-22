FROM fusuf/whatsasena:latest

RUN git clone https://github.com/onur55-tr/WhatsAsena1 /root/WhatsAsena1
WORKDIR /root/WhatsAsena1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
