FROM wordpress:latest

# Commandes pour installer mhsendmail
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y wget

# Installation et configuration de mhsendmail
RUN wget https://github.com/mailhog/mhsendmail/releases/download/v0.2.0/mhsendmail_linux_amd64 && chmod +x mhsendmail_linux_amd64 && mv mhsendmail_linux_amd64 /usr/local/bin/mhsendmail