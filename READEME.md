# es集群

账户密码： elastic/CdfXheFrmHaPkdjgq51c

测试指令：
```shell
curl -u elastic:CdfXheFrmHaPkdjgq51c -XPUT http://127.0.0.1:9200/bigdata_p
curl -k -u elastic:CdfXheFrmHaPkdjgq51c -H"Content-type:application/json" -XPOST http://127.0.0.1:9200/bigdata_p/product/1 -d '{"author" : "Doug Cutting"}'
curl -k -u elastic:CdfXheFrmHaPkdjgq51c   http://127.0.0.1:9200/syslog_20230228/_search
curl -k -u elastic:CdfXheFrmHaPkdjgq51c -H"Content-type:application/json" -XPOST http://127.0.0.1:9200/syslog_20230221/product/1 -d '{"author" : "Doug Cutting"}'
```

