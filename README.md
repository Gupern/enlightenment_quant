# enlightenment_quant
悟道 量化

# 本项目旨在于搜集悟道量化群的投资理念信息，以及共享常用的代码

# 目录结构

## 1. 投资理念

## 2. 共享代码

## 3. 开源项目
- 不重复造轮子，fock by equant `https://github.com/equant/equant`
- 目前专注于每日复盘，重点看T-1数据
- 采用django框架，sqlite数据库，方便每个投资者自己维护自己的投资理念信息，或者进行魔改。此外，用sqlite会更快，mysql的话加载数据太慢了。
- 参考网址：http://www.taodudu.cc/news/show-5852612.html?action=onClick
- 启动命令 参考README_bak.md
- 提交代码husky报错：删除./husky文件即可


## TODO
- [ ] T-1复盘大屏
- [ ] 回测功能（仿造backtrader，加载数据、策略、回测、可视化、仓位控制、手动调节）
- [ ] 实时盯盘功能（付费数据 or 爬虫）