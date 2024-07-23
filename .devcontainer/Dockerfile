# Use the official Hugo image as a base
FROM klakegg/hugo:latest

# Install any additional tools you need
RUN apk add --no-cache \
    git \
    bash

# Set the working directory
WORKDIR /workspace

# Expose port 1313 for Hugo server
EXPOSE 1313
