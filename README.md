# 期中实验
Android Midterm project
# 基础功能
## 一、时间戳显示
### 效果截图：

![9](https://user-images.githubusercontent.com/92290747/143764856-847c10ad-5f0c-4301-857c-5bd7d8ce6ea4.png)


1、时间戳位置在notelist_item.xml中添加TextView

![1](https://user-images.githubusercontent.com/92290747/143764699-a72f51c6-c862-4d1c-8d1d-d7ebcacefb09.png)

2、NoteList类的PROJECTION中添加以下字段

![2](https://user-images.githubusercontent.com/92290747/143764713-9c313917-0ad5-4559-8dcd-eb0649220291.png)

3、关键在NoteEditor类的updateNote方法中获取当前系统的时间，并对时间进行格式化：

![3](https://user-images.githubusercontent.com/92290747/143764721-a6e55299-8e4f-4d80-bb5a-f6dda6d9e5b3.png)


## 二、添加搜索栏
### 效果截图：
![10](https://user-images.githubusercontent.com/92290747/143764949-fd7163f6-b9e0-46d2-b8f3-3eb406a177b9.png)

![11](https://user-images.githubusercontent.com/92290747/143764956-99931836-c870-4d9d-ade6-0d6ca1e0b59d.png)

1、在list_options_menu.xml中添加搜索功能

![4](https://user-images.githubusercontent.com/92290747/143764727-c1561626-6250-4548-8369-f529b588017c.png)

2、在layout中新建查找笔记内容的布局文件note_search.xml

![5](https://user-images.githubusercontent.com/92290747/143764732-93e85ba2-ade3-4412-bd03-a6818e57cd76.png)

3、在NoteList类中的onOptionsItemSelected中新增查询的处理

![6](https://user-images.githubusercontent.com/92290747/143764733-a942fffb-1a8e-43ec-9e90-9d396c12bbd8.png)

4、关键新建一个NoteSearch类用于Search功能实现，并在string.xml中添加menu_search

![7](https://user-images.githubusercontent.com/92290747/143764737-ce12dfe9-a523-46f1-a0bb-f936df59565c.png)
![7 1](https://user-images.githubusercontent.com/92290747/143764741-ab0e8c92-ca8c-47aa-a1de-8fc0337631c0.png)

5、在AndroidManifast.xml中添加

![8](https://user-images.githubusercontent.com/92290747/143764830-6ecf7f8f-2d2d-41d8-a918-691733b962ae.png)

