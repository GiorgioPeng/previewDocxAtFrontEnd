# docx2html
> 不是一个功能性的js模块,而是一个使用mammmoth.js的踩过坑之后的示例,旨在帮助后人少踩坑  
> 一些小建议: 在线预览office可以优先考虑微软提供的接口(这个也有一些小坑,如果我用这个方法成功了,就没有这个示例了),其次才是使用mammoth.js 或者 sheet.js等实现  
__需要查看源码的话下载docx2html.html,longRangeConvert.js,mammoth.browser.min.js,uploadConvert.js 这几个就好,img里面是这个markdone的示例图__    
---  
>注:_mammoth.js卡了我很久的地方是 传入需要转化的文件的path,官方文档给定就是一个path,但是我个人测试了挺久之后发现需要传入一个file对象或者blob对象,如果有大佬有其他看法欢迎指点本人._  
---  
> 本示例为将docx文档转化成HTML格式(基于mammoth.js),可以实现在线预览功能,大致分为两个:  
- 上传文件时直接预览
- 预览远程服务器上存在的docx文件
---  
下面为示例图  
**示例打开的样子**  
![](./img/index.png)   
**预览上传的docx文档**  
![](./img/upload.png)   
**预览远程docx文档**  
![](./img/long_range.png) 
