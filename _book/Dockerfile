FROM arm32v7/debian:buster-slim

# Install dependencies and Node.js
RUN apt-get update && \
    apt-get install -y curl gnupg && \
    curl -sL https://deb.nodesource.com/setup_10.x | bash - && \
    apt-get install -y nodejs build-essential && \
    apt-get install -y npm

# Verify npm and node installation
RUN node -v && npm -v

# Configure npm to ignore SSL certificate errors
RUN npm config set strict-ssl false

# Install gitbook-cli
RUN npm install -g gitbook-cli

WORKDIR /gitbook

EXPOSE 4000 35729

CMD ["gitbook", "serve", "/gitbook"]
