# vagrant設定



docker run -d --privileged=true -p 6379:6379 -v /home/vagrant/conf/redis/redis.conf:/etc/redis/redis.conf -v myredis:/data --name myredis redis:5.0.3 redis-server /etc/redis/redis.conf --appendonly yes
