# 1688
扒取 1688 商家数据

## 步骤:
1. 运行 getSearchKeyWords.py, 得到 searchKeyWords.txt 关键字列表<br>
2. 运行 initKeyWordsHistoryDB.py, 得到 keyWordsHistory.db 初始化关键字搜索的历史库
3. 运行 getGoodsList.py, 得到 goods.db 商品库
4. 运行 initGoodsHistory.db 得到 goodsHistory.db 初始化商品搜索历史库
5. 运行 getCompanyInfo.py 得到最终的 company.db 公司信息库

还蛮好玩的，拿到了30万家公司的信息，不足点就是没开多线程，所以第5步太慢了...

## 2016.12.12 更新说明

因为 1688 的商户信息页面做了调整，多了一些新的内容，所以 getCompanyInfo.py 需要做一些修改，不然会报错。我懒得改了，这数据对我无用，有兴趣的朋友可以改改玩玩。
