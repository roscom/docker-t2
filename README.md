## docker-t2

initial docker test

see - https://semaphoreci.com/community/tutorials/dockerizing-a-ruby-on-rails-application

Notes
1. there is an issue with the redis port because 6379 is already used and changing to 6380 seems not to take effect. causes sidekiq to fail.	
2. also initialisation of the rails app fails on spring with spec

