FROM node:14-alpine
EXPOSE 3000
WORKDIR /FrontEnd
COPY ["node_modules.tar.gz", "/FrontEnd"]
COPY [".", "/FrontEnd"]
CMD ["npm", "start"]
