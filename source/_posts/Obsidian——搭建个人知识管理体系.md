---
title: Obsidian——搭建个人知识管理体系
date: 2024-05-18
categories:
  - Obsidian
tags:
  - "#Obsidian"
---

- *Author: KirkSung
- *Date: 2024-05-19
- *Link: 
- *Publisher: https://kirksung.github.io/ 
- *Notes: Obsidian——搭建个人知识管理体系
- *Tags:  #Obsidian 
 
> 通过行为设计匹配的新习惯，是我们在最忙碌、最没动力且状态最不好时，也能做到的行为。

# 极简三步，构建个人知识管理工作流


整体来讲，将个人知识管理工作划分为三个步骤：
- Inbox - I：输入，即知识、信息的获取
- Process - P：处理，加工，即对知识、信息进行要点提取、整合、理解、内化、总结等处理
- OutPut - O：输出，即写作、分享并获取反馈。

## Inbox：输入

不要想着【等有时间了就读】而把很多感觉看起来不错的文章一股脑儿地塞进收藏夹——那等待他们的命运一定是躺在收藏夹里吃灰。

## Process：加工

「读完」并非结束，而是开始——知识管理的开始。

知识加工方法，使用个人知识管理专家 Tiago Forte 提出的渐进式总结法（Progressive Summarization）。

所谓「渐进」，是Tiago Forte把知识加工分为了从 0 到 5 共六个层级，你不一定需要把每一个知识输入都严丝合缝地走完全部层级，但每一层级之间一定是循序渐进的，不能出现跃层。

![渐进式总结法](Obsidian——搭建个人知识管理体系/渐进式总结法.png)



- Layer 0：原始文本
	- 信息源文本
- Layer 1：捕捉信息
	- 所有划线部分，摘出来到一个文档中
- Layer 2：重中之重
	- 阅读第一层文档，把你仍然觉得眼前一亮、学到、感兴趣、有启发等等地地方加粗标记。
- Layer 3：优中之优
	- 再读一遍这个文档，以最审视、最挑剔的眼光，高亮你觉得最值得的部分。
- Layer 4：总结提取
	- 用自己的话对第2、3层做一下总结/
- Layer 5：重组输出
	- 对于一些要点，加入自己的思考、想法、例证、创造等，进行写作输出。结合三步构建个人知识管理工作流中的第三步OutPut。

不一定需要把每一个知识输入都严丝合缝地走完全部层级，但每一个层级之间一定是循序渐进的，不能出现跃层。

第1、2、3、4层都在同一个文档中进行，可以最大程度的保留上下文语境，不必担心回头看的时候一头雾水。第4、5层不一定每一篇笔记都设计到，只有值得的信息/知识才需要如此大费周章，对笔记进行思考。

## OutPut：输出

搭建完自己的个人知识管理体系后，更需的是进行思考、总结。

# Obsidian的一些个人设置

## Obsidian文件夹设置

	在Obsidian的文件夹设置方面，还是参考了PARA进行了设置，根据自己的实际需要和诉求，形成了几个自己的文件夹：
	- Daily 主要包含Daily、Weekly的计划、追踪及总结，包含年度的Montage
	- Computer Science and Technology 以自己的专业进行的命名，是长期关注的事情，贯彻于我学习和工作生涯。
	- Projects 是个人开展的基于兴趣或其他目的短期任务。比如我当前正在进行的通过Obsidian搭建个人知识管理体系、Hexo结合Github建立个人博客主页等，当知识管理工作流在未来的半年内有序顺利工作，个人博客熟练更新后当前的Project便成为完成状态，在很长的时间内不会进行更新。
	- Inbox 与Areas和Projects相关的内容、笔记或者剪切的文章，处于三步构建个人知识管理工作流中的第一步，作为Resources
	- Archives 处于生命周期之外的、不再关注的用来归档的项目，以减少对其他重要信息的干扰。
	- Templates Obsidian中的模板信息

## 笔记的分类
### Daily Note

主要包含Daily、Weekly的计划、追踪及总结，包含年度的Montage。根据个人的习惯主要，进行了以下的划分：

> [!info] Daily Weekly
> - To Do：任务计划
> - Tracking：任务追踪
> - Summary：总结

在Daily、Weekly的Tracking：任务追踪这个模块中，使用了间歇式日记的方式，在每个工作间歇、以时间戳为单位、采用类似日记的形式做的笔记。清空大脑，记录一下刚完成的事情；下一步行动，更具体的行动。

> [!info] Montage
> - 工作
> - 学习
> - 博客
> - 阅读
> - 健康
> - 旅行
> - 个人习惯
> - 感情

在年度Montage中主要区分了上下两篇，上篇是对年度的规划，下篇是对年度的总结。根据个人情况主要对正经事和不正经事进行了分类。

### 工作/学习笔记

根据极简三步，构建个人知识管理工作流中的相关描述，主要包含


> [!summary] Summary
> 对应渐进笔记的Layer 4，对原文要点进行总结提炼
> 

> [!NOTE] Notes
> 对应渐进笔记的Layer1 ~ Layer 3，用来筛选书籍/文章中的重要信息和知识点。
> 

## 内容输出

随个人习惯。

## 使用GitHub进行备份、同步

### 备份

网上有许多Obsidian使用GitHub进行备份的教程，在此不进行详细描述，主要包含

1. 创建Obsidian Valut

2. 本地Git安装，进行配置，生成密钥
```sh
git config --global user.name "username"
git config --global user.email "email address"
```
将username 和 email address替换为自己的用户名和邮箱地址
```sh
ssh-keygen -t rsa -C "email address"
```
生成密钥，根据shell中的提示，找到id_rsa.pub文件，打开复制全部内容

3. GitHub个人setting中添加SSH and GPG keys：粘贴
4. Github 创建仓库，记得勾选Private，在仓库的Code中，复制SSH地址 git@github.com:xxx/xxxx.git。
5. Obsidian Valut目录下，右键，进行git操作，若不熟悉git的相关操作，可进行搜索
```sh
git init
git add .
git commit - m "init ob valut"
git remote add origin git@github.com:xxx/xxxx.git
git push -u origin main
```
6. Obsidiant设置-第三方插件，关闭安全模式，插件市场搜索并安装Git插件（需科学上网），若上述Git设置无问题，Git只需要简单设置便可实现Obsidian 仓库自动备份至GitHub对应库。

详细教程可具体搜索，在此仅进行简单描述。
### Android客户端进行同步

目前仅实现通过Android客户端进行查看，每次查看前通过MGit拉取最新的库到本地。

安卓手机下载安装MGit App，部分手机无法使用Google Play或通过Google Play下载的MGit无法使用，所以下载F-Droid来安装MGit。主要步骤如下：
1. MGit设置中进行Git配置，设置用户名、用户邮箱，点击SSH Keys，右上角点击+添加密钥，复制，进入GitHub个人Setting中添加SSH and GPG keys
2. MGit设置，进行repos的根存储位置设置，我使用了/storage/emulated/0/我的文档
3. 右上角+，克隆仓库，输入远程地址，将仓库克隆到本地

安卓手机，下载Obsidian App，打开克隆到本地的仓库便可以进行查看。Obsidian App修改内容后，通过MGit进行提交。

目前没有实现通过第三方Git插件实现自动同步的操作。
移动端还是希望，只进行查看的操作。

## 当前插件介绍

> [!example] Calender
> 右侧显示日历，可快速定位Daily、Weekly，如果当日存在未完成的Task To Do，日期下会存在空心圆点。
> 
>

> [!example] Git
> 通过Git插件实现Obsidian Valut到Github的自动同步

> [!example] Editing Toolbar
> 在编辑区域显示Markdown工具栏，方便文档编写

> [!example] Linter
> 格式化工具

> [!example] Custom Frames -Archives
> 将Web应用添加到Obsidian中，通过命令行进行快速打开，目前添加了MicroSoft To Do。
> 没有进行深入的使用

> [!example] Clear Unused Images
> 删除没有使用的图片。删除后的图片路径为跟存储路径下的.Trash
> 注意跟目录下编写.gitignor写入/.Trash/

> [!example] Paste image rename
> 配合设置中，文件与链接-附件默认存放路径，设置为当前文件所在文件夹下指定的子文件夹中，设置子文件夹名称为“attachments”
> 设置AutoRename，在文件所在文件夹下的子文件夹中，便能看到Rename的图片
>

# 参考 

1、[极简三步、我的个人知识管理工作流](https://sspai.com/post/81926)  CR： [小梨笔记](https://sspai.com/u/chgqadc5/updates)
2、[用Obsidian搭建我的个人知识管理工作流](https://sspai.com/post/82012) CR：[小梨笔记](https://sspai.com/u/chgqadc5/updates)
3、[我对PARA的理解与时间](https://sspai.com/post/78349) CR：[Jiang](https://sspai.com/u/jiangzilong/updates)
4、[玩转Obsidian 03：间歇式日记](https://sspai.com/post/63674)  CR：[贤者时间_王掌柜](https://sspai.com/u/5b3wva6y/updates) 
