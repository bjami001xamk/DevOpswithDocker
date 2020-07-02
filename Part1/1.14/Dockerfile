FROM ruby:2.6.0
WORKDIR /testia
EXPOSE 3000
COPY . /testia
RUN apt-get update && apt-get install nodejs -y && bundle install && rails db:migrate
CMD [ "rails", "s" ]