# a-python-spider-for-ganji.com
parsing second-hand goods information from ganji website.
1."channel_extracing" module is used to parsing all links of second-hand categaries.
2."page_parsing" module includes two spiders, the spider1 is used to parsing all goods links from "channel_list", the spider2 is used to parsing detailed information of each good.
3.use multiprocess to improve the parsing speed.
4.use proxy_ip to solve the ip blockade from ganji website.
5."count" module is used to count the quantity of items.
