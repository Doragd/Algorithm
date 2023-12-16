# 🎯 Usage

算法题练习记录博客（基于GitHub Action和GitHub Issue实现）。

可通过提交issue，自动将刷题记录更新在项目的README.md中，并将issue内容备份在项目backup文件夹下。

## Step 1: fork该项目

激活GitHub Actions功能
<img width="1417" alt="image" src="https://github.com/Doragd/Algorithm/assets/26213546/1817745f-5552-41fe-84fc-1137c8882b34">

打开fork项目的issues功能
* 点击下图所示按钮
<img width="1033" alt="image" src="https://github.com/Doragd/Algorithm/assets/26213546/b3800afe-98c1-4358-8c3c-03d48b442be1">
* 进入到setting页面，在这一页往下翻
<img width="1328" alt="image" src="https://github.com/Doragd/Algorithm/assets/26213546/eab6f005-0165-4b46-a4b3-e3379cb71351">
* 找到Features一节，然后勾选Issues
<img width="1275" alt="image" src="https://github.com/Doragd/Algorithm/assets/26213546/12e2f7c6-064d-46b0-b47b-a7a80018935a">


## Step 2: 提交issue

每当你刷完一道算法题，可在你的项目上提交一个issue：
* issue title可以是所刷题目的标题，也可以是其他任意你想记录的笔记标题。
* 同时，你也可以为这个issue打上label，例如二叉树、搜索。
* 将你想记录的对这道题的思考作为issue的description。
[示例issue](https://github.com/Doragd/Algorithm/issues/3)

<img width="1239" alt="image" src="https://github.com/Doragd/Algorithm/assets/26213546/9d6cabf6-9af1-487e-bcde-3c459a3c0892">

## Step 3: 查看效果

此时[README.md](README.md) 中

    1） Calendar部分会基于issue创建日期在日历上标记一个star

    2） Records部分会新增一行记录, 各列分别记录：

         #: issue号
         Title: issue title（点击可跳转至你所创建的issue）
         Tag： issue Labels
         Date: issue创建时间
    
同时，backup文件夹下会以“issue号+#+的issue title"作为文件名，生成一个对issue的备份文件，备份issue的description。该issue下所有后续的comments也会被记录下来。[示例备份文件](backup/2#110.%20平衡二叉树.md)

## Step 4: 编辑和更新

当你编辑issue的title或description、修改issue的Labels、issue有新comment或者issue的comment被编辑时, [README.md](README.md)和backup文件夹下issue的备份文件都会进行相应更新

