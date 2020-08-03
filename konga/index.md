初始化konga数据库  

docker run --rm pantsel/konga -c prepare -a postgres -u postgres://root:123456@192.168.40.91:5432/konga