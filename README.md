Boluoboluomi API
============

The API of a funny website boluoboluomi.com

Resource URL
------------
- http://boluoboluomi.com/api/{section}?per_page={pageSize}&page_th={pageNumber}

参数
----

参数名称                  | 描述
------------------------- | ------
**section**<br>*必需*     | 现在支持的参数值可以是(`hot`,`trending`,`fresh`)
**pageSize**<br>*必需*    | 每页加载记录条数，如`10`
**pageNumber**<br>*必需*  | 加载第几页，如：加载第一页，则写`0`

请求实例
--------

**GET** `http://www.boluoboluomi.com/api/hot?per_page=10&page_th=0`

        {
                data: [
                          {
                              id: "101",
                              gid: "Cziaxlr.",
                              score: "86",
                              title: "我TM坐着好好的招谁惹谁了啊",
                              url: "Cziaxlr.jpg",
                              comments: "5",
                              images: {
                                    small: "http://gaoxiao1.qiniudn.com/Cziaxlr.jpg/460s",
                                    large: "http://gaoxiao1.qiniudn.com/Cziaxlr.jpg/700b"
                              }
                          },
                          ···
                ]
        }

更多接口
--------
开发中，敬请期待！


最佳实践
--------
敬请期待！

官方网站
--------
[菠萝菠萝蜜](http://http://www.boluoboluomi.com/)
