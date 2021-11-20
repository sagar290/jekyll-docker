FROM jekyll/jekyll

WORKDIR /var/www/jekyll

COPY . /var/www/jekyll

COPY entrypoint.sh /var/www/jekyll

RUN chmod +x /var/www/jekyll/entrypoint.sh

RUN chmod -R 777 /var/www/jekyll/entrypoint.sh

EXPOSE 4000

ENTRYPOINT ["/bin/bash", "./entrypoint.sh"]
