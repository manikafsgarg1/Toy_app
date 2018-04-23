# README

This README would normally document whatever steps are necessary to get the
application up and running.

CMD - rails new toy_app

CMD - cd toy_app/

Changes in gem file
group :production do
  gem 'pg', '0.20.0'
end

CMD - bundle install --without production

CMD - rails generate scaffold User name:string email:string

CMD - rails db:migrate

CMD - rails generate scaffold Micropost content:text user_id:integer

CMD - rails console
