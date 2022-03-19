FROM fusuf/whatsasena:latest

RUN git clone https://github.com/skyeshan/ruki /root/ruki
WORKDIR /root/ruki/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
