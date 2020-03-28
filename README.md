# CookBook-KG
A knowledge graph for Chinese cookbook（中式菜谱知识图谱）\
\
本项目开发的系统名称为**AI Food Time**，中文名为**爱食光**  
通过收集网上完全公开的有关中式菜谱的数据，经过**数据清洗和分析**，转换为**知识图谱的存储结构**，并进行可视化展示等功能，为热爱美食与烹饪的人们提供方便快捷的中式菜谱服务，并以知识图谱的形式直观显示出不同菜品的关系及所用原料，在生活中具有很大的实际应用需求，包括：
+ 一类菜品的不同具体做法，例如水煮鱼包括麻辣水煮鱼、小清新版水煮鱼和家常版水煮鱼等
+ 通过菜品与食材的关联关系，可以查询家中现有食材可以烹饪哪些菜品
+ 可以直接显示出每种菜品所需主料，辅料，配料及其具体数量和烹饪方法，与网上的一些菜谱网页相比更加简单直观
## 功能使用
### 可视化展示及搜索：
![image](https://github.com/ngl567/CookBook-KG/blob/master/miniviz-1.png)  ![image](https://github.com/ngl567/CookBook-KG/blob/master/miniviz-2-fig.png)  
同一类实体用相同颜色的节点表示，鼠标位于某个节点上方时显示其相关联的其它实体和之间的关系名称
具有同一类实体显示开关，节点显示模式转换，并支持搜索功能
+ **mini**版：包含10大类，**50**种菜品之间的关联关系，包括菜品制作的各种食材和制作步骤  
mini版的Github Page[**访问入口**](https://ngl567.github.io/CookBook-KG/)
+ **pro**版：包含**362**大类，**八千多**种菜品之间的关联关系，包括菜品制作的各种原料和制作步骤
