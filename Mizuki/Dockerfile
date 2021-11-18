FROM fusuf/whatsasena:latest
##Queen Mizuki
RUN git clone https://github.com/dinukahimsara1/Mizuki /root/QueenMizuki
WORKDIR /root/QueenMizuki/
ENV TZ=Europe/Istanbul
RUN yarn add supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
