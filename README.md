# README  
## 说明
本项目的dashboard使用Github Pages与Jekyll直接将markdown文件渲染成html    
只需添加更改markdowm文件即可改变网站的内容，免去繁琐的命令部署过程  

## 提交流程
添加/更改md文件  
需要时更改index.md内相应链接  

## 命名规范
XX-XX-File-Name.md  
XX为index内相应序号，文件名全小写，如有空格使用"-"代替  
示例：02-team-profile.md, 06-01-usecase-diagram.md  

## 链接跳转
```[text](xx-file-name)```  
先将文字用[]括起来，将导向文件名添加到括号内  
示例：```分工情况详见[此链接](02-team-profile)```  

## markdown表格
如出现表格在html中无法正常渲染的情况，请检查以下事项：  
1. 表格上下方需要有回车与其他元素隔开  
2. 表头分隔符至少需要有三个"-", e.g.|---|---|  
3. 列表每一行最后至少要有4个空格  

## 参考资料
你也想搭建如此简洁方便的dashboard网站？请浏览以下网站  
> [Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/)


