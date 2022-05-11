FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ASWINMATRIX/Sulthan_ /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/ASWINMATRIX/kaztroser

CMD ["node", "bot.js"]
