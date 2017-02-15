# 前言

ElasticStack是原ELKStack在5.0版本加入Beats套件后的新称呼。

ElasticStack在最近两年迅速崛起，成为机器数据分析，或者说实时日志处理领域，开源界的第一选择。和传统的日志处理方案相比，ElasticStack具有如下几个优点：

* 处理方式灵活。Elasticsearch 是实时全文索引，不需要像 storm 那样预先编程才能使用；
* 配置简易上手。Elasticsearch 全部采用 JSON 接口，Logstash 是 Ruby DSL 设计，都是目前业界最通用的配置语法设计；
* 检索性能高效。虽然每次查询都是实时计算，但是优秀的设计和实现基本可以达到全天数据查询的秒级响应；
* 集群线性扩展。不管是 Elasticsearch 集群还是 Logstash 集群都是可以线性扩展的；
* 前端操作炫丽。Kibana 界面上，只需要点击鼠标，就可以完成搜索、聚合功能，生成炫丽的仪表板。



