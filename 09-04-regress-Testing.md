### 回归测试报告

| 版本 | 测试时间   | 测试员  |
| ---- | ---------- | ------- |
| v0.1 | 2018.06.27 | 李佳铭 |

1. ##### 测试概述

   本次回归测试主要以挣闲钱团队[Tower管理工具](https://tower.im/teams/810695/projects/132/)记录的所有bug为基础，检查第一轮测试发现的bug是否已经修复，以及是否产生新的bug

2. ##### 测试环境

- 商家端设备：Win10 + Chrome浏览器


3. ##### 测试结果

- 已解决的第一轮测试发现的bug

  | 序号               | 功能                                                         | 是否通过（Y/N） |
  | ------------------ | ------------------------------------------------------------ | --------------- |
  | [功能性bug] 1      | 问卷可以再次填写                                           | Y               |
  | [功能性bug] 2      | 问卷过期处理有问题                                         | Y               |
  | [功能性bug] 3      | [发现问答可以再次填写的bug                                  | Y               |
  | [功能性bug] 4      | 发现问答过期处理有问题                                     | Y               |
  | [功能性bug] 5      | 发布的问题在问题中间出现，排序有问题                          | Y               |
  | [功能性bug] 6      | 发布的问卷在问卷中间出现，排序有问题                          | Y               |
  | [功能性bug] 7      | 可以充值0元                                                 | Y               |
  | [非功能性bug] 8   | 发现已经注册过的邮箱注册没有错误提示                         | Y               |
  | [非功能性bug] 9   | 页面缩小后问卷显示有问题                                     | Y               |
  | [需求缺失bug] 10   | 没有提现功能                                                 | Y               |
  | [易用性bug] 11     | 问卷发布日期选择困难                                    | Y               |
  | [易用性bug] 12     |                       | Y               |
  | [易用性bug] 13     | 问卷发布添加选项按钮比较隐蔽| Y               |

- 未解决的第一轮测试发现的bug

/*
  | 序号             | 功能                                                         | 是否通过（Y/N） |
  | ---------------- | ------------------------------------------------------------ | --------------- |
  | [需求缺失性bug]1 | [商家端]缺少菜品排序的功能，包括普通编辑模式下拖动卡片排序和快速编辑模式下拖动列表项排序 | N               |
  | [需求缺失性bug]2 | [商家端]快速编辑模式下，不可上传菜品图像                     | N               |
  | [可靠性bug]3     | [商家端]工具栏刷新退出                                       | N               |
  | [易用性bug] 4    | [商家端]网络断开后再连接，原本已登录的页面不变但功能失效，没有“重新登录”的提示语 | N   
*/
4. ##### 测试分析

从测试结果看来，bug已经基本解决，程序可以满足普通人的需求。