FROM httpd:2.4.35
ADD ./public-html/ /usr/local/apache2/htdocs/
RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get install -y curl software-properties-common
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash - 

RUN apt-get install -y nodejs

RUN npm i bestzip@2.1.0