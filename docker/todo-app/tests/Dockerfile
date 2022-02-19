FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
COPY ["node_modules.tar.gz", "/tests"]
COPY [".", "/tests"]
CMD ["npm", "test"] 
