# docker-test
initial docker

see - https://semaphoreci.com/community/tutorials/dockerizing-a-ruby-on-rails-application

docker files are backed up to work/docker.tar.gz 

app is docker-t2 in github

NB: there is an issue with the redis port because 6379 is already used and changing to 6380 seems not to take effect.
	causes sidekiq to fail.
	
	also initialisation of the rails app fails on spring with spec

