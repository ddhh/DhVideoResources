# DhVideoResources
## 80s网站的url
> 用Jsoup从80s上抓数据

//base_url
BASE_URL = http://www.80s.tw

//电影
MOVIE_URL = /movie/list
                       /{1}-{2}-{3}-{4}-{5}-{6}
                        {1}:[1-9 a-y]   //类型
                        {2}:[2016-2004] //年份
                        {3}:[1-9 a-f]   //地区
                        {4}:[1-7]       //语言
                        {5}:[h,g]       //h-热门；g-好评   
                        {6}:[p1,p2,...,pn]
//电视剧
TVPLAY_URL = /ju/list
                    /{1}---{2}-{3}-{4}-{5}
                     {1}:[1-f]           //分类
                     {2}:[2016-2004]
                     {3}:[9-12]
                     {4}:[h,g]           //h-热门；g-好评
                     {5}:[p1,p2,...,pn]  //换页

//动漫
COMIC_URL = /dm/list
                    /{1}----{2}-{3}-{4}
                     {1}:[l,j]           //l-连载；j-剧场版
                     {2}:[14]            //固定的
                     {3}:[h,g]           //h-热门；g-好评
                     {4}:[p1,p2,...,pn]  //换页
//综艺
VARIETY_URL = /zy/list
                      /----{1}-{2}-{3}
                      {1}:[4]             //固定的
                      {2}:[h,g]           //h-热门；g-好评
                      {3}:[p1,p2,...,pn]  //换页
//热门
HOT_URL = /hot

//专题
SPECIAL_URL = /zhuanti
                      /list/-p{num}   //翻页
              /tag/{num}  //进入专题

//最近更新
LAST_UPDATE_URL = /top/last_update
                      /last_update_list/{num} //详细
//
