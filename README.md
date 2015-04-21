Note: 所有的脚本执行都是./sample.stp -x worker_pid test_uri的形式。
其中worker_pid是指定fastcache的worker的pid，test_uri是请求的uri部分
例如：./sample.stp -x 2240 "/file/2000/debug.html"

1. hitandmiss.stp: 查看一个url的hit和miss状态
2. upstream.stp: 查看一个请求的回原ip信息