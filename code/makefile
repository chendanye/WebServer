target = webserver
obj = main.cpp http_conn.cpp lock.cpp server.cpp sql_connection_pool.cpp log.cpp lst_time.cpp


$(target):$(obj)
	g++ $(obj) -o $(target) -lpthread -lmysqlclient -std=c++11

clean:
	rm -r $(target)
