# Shared Notes

Description: This files is a description for project shared notes.

Current Collaborator: yyc & zzjc

---

## Target

本项目的目的是建立一个能够让用户共享笔记，讨论学术相关话题的社区。想到这个项目的原因是在考试周复习是，发现通过和同学分享笔记，交流课程内容能够极大地提高复习的效率。同时，往届ta的rc slides和piazza上一些比较精彩的问题能够给我带来很大的启发。因此，我们希望能够建立一个共享笔记，slides以及能够讨论学习问题的平台。

### Problem

- 笔记没有办法分享
- Ta的rc slides没有办法传承
- 同学在piazza上的问题仅限于参加课程人员可以看到
- 课程piazza上同学不能讨论于课程相关性不强的内容（例如285 piazza上不能讨论ml相关的数学问题）

### Needs

- 共享笔记
- 传承TA RC slides
- 可以自由讨论问题的社区

### Solution

一个可以做到如下内容的平台

- 允许用户上传笔记，slides
- 允许用户对资源进行评论
- 允许用户创建tag并基于此进行讨论

---

## Feature

项目将基于[memos](https://github.com/usememos/memos)开发（感谢向哥提供的信息)。除了memos固有的feature，以上之前讨论过的功能，我们会添加以下功能

- 对于文件进行批注，讨论（类似于微信读书）
- 收藏（类似于书签或者github的star）
- 允许对文件进行复刻
- 下载文件到本地
- 允许用户协作或者Pull request

---

## Roadmap

上述项目依旧有许多需要解决的问题

- 文件存储策略
  - 目前仅支持markdown，计划支持latex
  - 需要完成markdown和latex的在线预览
  - 历史版本，文件复刻的储存（占用资源过多的时候可能需要删除某些版本）
  - 图片等大文件的储存
- HC
  - 为防止hc问题，可能需要用户实名
  - 提交需要经过hc或者维护者的审核or举报制度？
