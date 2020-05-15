FROM maven:alpine
RUN apk --update add git && \
    echo "[user]" >> ~/.gitconfig && \
    echo "name = Jenkins" >> ~/.gitconfig && \
    echo "email = jenkins@local.com" >> ~/.gitconfig && \
    rm -rf /var/lib/apt/lists/* && \
    rm /var/cache/apk/*
