FROM node:14-alpine
WORKDIR /backEnd
EXPOSE 3001
ADD ["node_modules.tar.gz", "/backEnd"]
COPY [".", "/backEnd"]
CMD ["npm", "start"] 