FROM quay.io/lyfe00011/md:beta
RUN git clone https://github.com/sanukanimsath/zunamic-multi-device-bot.git /root/zunamic-multi-device-bot/
WORKDIR /root/zunamic-multi-device-bot/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
