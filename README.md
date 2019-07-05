# pysogo

这是一个调用搜狗搜索的简单模块

  from pysogo import sogo
  
  bro = sogo.SogoEngine()
  
    # 搜索微信
    wx_bro = bro.search_weixin(query='网络编程')
    for part in wx_bro:
        print(part)
      
      
    # 搜索知乎
    zh_bro = bro.search_zhihu(query='网络编程')
    for part in zh_pro:
        print(part)
