# 20TeamB_Scrapy

![](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1584532164140&di=3b46722d88f68aa0468456b6b39717b2&imgtype=0&src=http%3A%2F%2Fpic2.zhimg.com%2Fv2-bfebe25b10c07cfc94b66d120a76d492_1200x500.jpg)

Scrapy是一个基于python的，快速的高级web crawling和web scraping框架，用于对网站进行爬网并从其页面提取结构化数据。它可以用于广泛的用途，从数据挖掘到监控和自动化测试。

## B组成员

- **汪凌风**
- 明昊
- 邵志钧
- 汪丽萍
- 闫奕涛
- 郑泽西

## 当前进度

- [x] 项目介绍
- [x] 项目准备
- [x] 实验一：软件需求分析
- [x] 实验二：软件需求评审
- [x] 实验三：软件产品改进与展示
- [x] 实验四：软件测试
- [x] 实验五：软件测试评审
- [x] 实验六：软件进度计划与控制
- [x] 实验七：配置管理
- [x] 实验八：工作量估计与统计分析
- [ ] 实验总结

## 文件格式说明

本节对整个项目所有文档所设计文件格式进行说明。

| 文件格式 | 说明                                                         |
| -------- | ------------------------------------------------------------ |
| .docx    | Word格式，用于存放文本，需要使用Microsoft Word打开。         |
| .md      | Markdown格式，用于存放会议记录补充或问题反馈文本。           |
| .pdf     | PDF格式，用于兼容不同机型的展示效果，包括word终稿等文档。    |
| .pptx    | PowerPoint格式，用于幻灯片制作与展示，需要Microsoft PowerPoint打开。 |
| .xls     | Excel格式，用于记录瓶身问题、会议记录等内容，需要Microsoft Excel打开。 |

## 文件结构说明

| 路径               | 说明                                                         |
| ------------------ | ------------------------------------------------------------ |
| /更新日志.txt      | 项目更新记录                                                 |
| /过程管理          | 存放会议记录、问题反馈等文件                                 |
| /幻灯片            | 存放项目展示所使用的幻灯片文件                               |
| /评审问题清单汇总  | 存放评审环节结束后反馈得到的问题表格等文件                   |
| /实验内容          | 分类存放包括项目准备阶段和实验[1-8]在内的各阶段实验输出的的产物和成果 |
| /源码              | 存放开发过程中的Demo和实例                                   |
| /project管理       | 存放Microsoft Project文件，记录项目管理内容                  |
| /README.md         | 项目说明                                                     |
| /过程管理/会议记录 | 记录小组成员日常会议的时间、地点、工作任务和会议内容         |
| /过程管理/问题追踪 | 记录小组成员在课堂上得到的问题反馈和笔记                     |

## 文件结构详情

```
|-- 20TeamB_Scrapy
    |-- .gitignore
    |-- README.md
    |-- 更新日志.txt
    |-- 0-参考资料
    |   |-- readme.md
    |-- 1-过程管理
    |   |-- 会议记录
    |   |   |-- 202003151400会议记录补充.md
    |   |   |-- 202003212030会议记录补充.md
    |   |   |-- 202003281400会议记录补充.md
    |   |   |-- 202004041500会议记录补充.md
    |   |   |-- 202004251530会议记录补充.md
    |   |   |-- 会议记录-202003072000.xlsx
    |   |   |-- 会议记录-202003151400.xlsx
    |   |   |-- 会议记录-202003212030.xlsx
    |   |   |-- 会议记录-202003241530.xlsx
    |   |   |-- 会议记录-202003281400.xlsx
    |   |   |-- 会议记录-202004011400.xlsx
    |   |   |-- 会议记录-202004041500.xlsx
    |   |   |-- 会议记录-202004081400.xlsx
    |   |   |-- 会议记录-202004111500.xlsx
    |   |   |-- 会议记录-202004151400.xlsx
    |   |   |-- 会议记录-202004251530.xlsx
    |   |   |-- 会议记录-202004291400.xlsx
    |   |   |-- 会议记录-202005031400.xlsx
    |   |   |-- 会议记录-202005061400.xlsx
    |   |   |-- 会议记录-202005091400.xlsx
    |   |   |-- 会议记录-202005131400.xlsx
    |   |   |-- 会议记录-202005161400.xlsx
    |   |   |-- 会议记录-202005201430.xlsx
    |   |   |-- 会议记录-202005231400.xlsx
    |   |   |-- 会议记录-202005271400.xlsx
    |   |   |-- 会议记录-202005301400.xlsx
    |   |   |-- 会议记录-202006031400.xlsx
    |   |-- 问题反馈
    |   |   |-- 2020.03.13汇报问题反馈.md
    |   |   |-- 2020.03.20汇报问题反馈.md
    |   |   |-- 2020.03.27汇报问题反馈.md
    |   |   |-- 2020.04.03汇报问题反馈.md
    |   |   |-- 2020.04.10汇报问题反馈.md
    |   |   |-- 2020.04.17汇报问题反馈.md
    |   |   |-- 2020.04.24汇报问题反馈.md
    |   |   |-- 2020.05.08汇报问题反馈.md
    |   |   |-- 2020.05.15汇报问题反馈.md
    |   |   |-- 2020.05.22汇报问题反馈.md
    |   |   |-- 2020.05.29汇报问题反馈.md
    |   |-- 问题反馈
    |   |   |-- 实验计分统计表格v1.1.0.docx
    |   |   |-- 实验计分统计表格v1.2.0.docx
    |   |   |-- 实验计分统计表格v1.3.0.docx
    |   |   |-- 实验计分统计表格v1.4.0.docx
    |   |   |-- 文档质量与互评质量评价.xlsx
    |   |   |-- 第4-6次互评.xlsx
    |   |   |-- 第一次实验互评.xlsx
    |   |   |-- 第二次实验互评.xlsx
    |   |   |-- 第三次实验互评.xlsx
    |-- 2-幻灯片
    |   |-- 第2周-项目介绍.pptx
    |   |-- 第3周-项目计划.pptx
    |   |-- 第4周-需求分析.pptx
    |   |-- 第5周-需求评审.pptx
    |   |-- 第6周-需求评审(二）.pptx
    |   |-- 第7周-实验6-8总结.pptx
    |   |-- 第8周-软件实现(一）.pptx
    |-- 3-评审问题清单汇总
    |   |-- readme.md
    |-- 4-实验内容
    |   |-- 0-项目准备阶段
    |   |   |-- 20B_基于Scrapy的WebUI开发_项目计划书V1.0.0.docx
    |   |   |-- 20B_基于Scrapy的WebUI开发_项目计划书V1.1.0.docx
    |   |   |-- 20B_基于Scrapy的WebUI开发_项目计划书v1.2.0.docx
    |   |   |-- 项目计划书V1.2.0.docx
    |   |-- 1-实验1：软件需求分析
    |   |   |-- readme.md
    |   |   |-- 截图
    |   |   |   |-- scrapyRUCM
    |   |   |   |   |-- 下载页面.png
    |   |   |   |   |-- 发送请求.png
    |   |   |   |   |-- 处理Item.png
    |   |   |   |   |-- 接收请求.png
    |   |   |   |   |-- 生成请求.png
    |   |   |   |   |-- 解析响应.png
    |   |   |   |   |-- 调度模块.png
    |   |   |   |-- webRUCM
    |   |   |       |-- 在线编辑调试.png
    |   |   |       |-- 生成词云.png
    |   |   |       |-- 管理脚本.png
    |   |   |       |-- 自动化生成脚本.png
    |   |   |       |-- 选择优化.png
    |   |   |-- 文档
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求分析说明书V1.0.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求分析说明书v1.1.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v1.1.1.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v1.1.2.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.0.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.1.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.1.1.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.2.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.3.0.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_项目需求规格说明书v2.4.0.docx
    |   |   |-- 模型
    |   |       |-- 软工B组_Scrapy.mdj
    |   |-- 2-实验2：软件需求评审
    |   |   |-- 需求评审表单.docx
    |   |   |-- 0-评审标准
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_需求规格说明书评审单.docx
    |   |   |   |-- 20B_基于Scrapy的WebUI开发_需求评审表单.docx
    |   |   |-- 1-对其他组的评审结果
    |   |   |   |-- B对A组评审单.docx
    |   |   |   |-- B对C组评审单.docx
    |   |   |   |-- B对D组评审单.docx
    |   |   |   |-- B对I组评审单.docx
    |   |   |-- 2-收到的评审意见反馈
    |   |       |-- B组对A组评审意见反馈.docx
    |   |       |-- B组对C组评审意见反馈.docx
    |   |       |-- B组对D组评审意见反馈.docx
    |   |       |-- B组对I组评审意见反馈.docx
    |   |-- 3-实验3：软件产品改进与展示
    |   |   |-- 0-文档
    |   |       |-- 20B_基于Scrapy的WebUI开发_项目设计文档v1.0.0.docx
    |   |-- 4-实验4：软件测试
    |   |   |-- 0-文档
    |   |       |-- 0-测试需求规格说明书
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书V1.2.1.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.3.0.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.0.0.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.1.0.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.1.1.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.1.2.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.1.3.docx
    |   |       |   |-- 20B_基于Scrapy的WebUI开发_测试需求规格说明书v1.2.0.docx
    |   |       |-- 1-测试结果分析报告
    |   |           |-- 20B_基于Scrapy的WebUI开发_测试结果分析报告v1.0.0.docx
    |   |           |-- 20B_基于Scrapy的WebUI开发_测试结果分析报告v1.0.1.docx
    |   |           |-- 20B_基于Scrapy的WebUI开发_测试结果分析报告v1.1.0.docx
    |   |           |-- 20B_基于Scrapy的WebUI开发_测试结果分析报告v1.1.1.docx
    |   |-- 5-实验5：软件测试评审
    |   |   |-- 0-文档
    |   |       |-- 0-评审标准
    |   |       |   |-- 测试评审报告.docx
    |   |       |   |-- 软件测试需求规格说明书检查单.docx
    |   |       |   |-- 软件问题报告.docx
    |   |       |-- 1-对其他组评审结果
    |   |       |   |-- B对E组测试评审报告.docx
    |   |       |   |-- B对E组软件问题报告.docx
    |   |       |   |-- B对F组测试评审报告.docx
    |   |       |   |-- B对F组软件问题报告.docx
    |   |       |   |-- B对G组测试评审报告.docx
    |   |       |   |-- B对G组软件问题报告.docx
    |   |       |   |-- B对H组测试评审报告.docx
    |   |       |   |-- B对H组软件问题报告.docx
    |   |       |-- 2-其他组对本组评审结果
    |   |           |-- 20F_对B组测试需求说明书评审单.docx
    |   |           |-- 20F_对B组软件问题报告.docx
    |   |           |-- E组对B组软件问题汇总.docx
    |   |           |-- E评审B组.docx
    |   |           |-- G-B_执行结果分析报告评审表格.docx
    |   |           |-- G-B_测试需求规格说明书评审表格.docx
    |   |           |-- H-B组测试需求评审汇总.docx
    |   |           |-- H-B组软件问题汇总.docx
    |   |-- 6-实验6：软件进度计划与控制
    |   |   |-- readme.md
    |   |-- 7-实验7：配置管理
    |   |   |-- readme.md
    |   |-- 8-实验8：工作量估计与统计分析
    |       |-- readme.md
    |-- 5-project管理
        |-- 1.mpp
        |-- readme.md
        |-- 项目计划安排.mpp
        |-- 项目计划安排v2.0.0.mpp
        |-- 项目计划安排v3.0.0.mpp
```