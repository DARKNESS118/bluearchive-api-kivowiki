# api.kivo.wiki 使用方法

本来想写返回值示例的，但是返回值动辄几百上千行的，太多了...
###  1.获取角色列表
#### 用法:
````https://api.kivo.wiki/api/v1/data/students/?page=[INT1]&page_size=[INT2]````
|变量名|含义|
|----|----|
|`[INT1]`|当前请求的页数|
|`[INT2]`|当前页数显示角色的数量|



*`skin`,`skin_jp`,`skin_zh_tw`为当前角色皮肤的名称(如泳装，圣诞)，`skin`是简体国服中文，`skin_jp`是日服日文，`skin_zh_tw`是国际服繁体中文，如果未实装，或当前角色为原皮，则为空*

---
### 2.获取详细角色信息
#### 用法:
```https://api.kivo.wiki/api/v1/data/students/[INT]```
|变量名|含义|
|----|----|
|`[INT]`|请求的角色的ID|

---

### 3.获取社团信息
#### 用法
```https://api.kivo.wiki/api/v1/data/relations/[INT]```
|变量名|含义|
|----|----|
|`[INT]`|请求的社团ID|

---

### 4.获取物品信息
#### 用法
```https://api.kivo.wiki/api/v1/data/items/[INT]```
|变量名|含义|
|----|----|
|`[INT]`|请求的物品ID|



*学生的装备，爱用品，礼物，以及各种材料等均为物品，不同种类的物品返回内容可能会有较大差别*

---

### 5.获取卡池信息
#### 用法
```https://api.kivo.wiki/api/v1/data/pick_up/?server=[STR]```


|变量名|含义|
|----|----|
|`[STR]`|请求的游戏版本，`cn`为国服，`jp`为日服|



*返回值为学生ID*

---
### 6.获取新闻事件
#### 用法
```https://api.kivo.wiki/api/v1/news/?page=[INT1]&page_size=[INT2]```
|变量名|含义|
|----|----|
|`[INT1]`|当前请求的页数|
|`[INT2]`|当前页数显示新闻的数量|

`

---
### 7.获取本周生日的学生
#### 用法

```https://api.kivo.wiki/api/v1/data/students/birthday/week```

---

### 8.获取当前的活动
#### 用法

```https://api.kivo.wiki/api/v1/data/event/now?server=[STR]```
|变量名|含义|
|----|----|
|`[STR]`|请求的游戏版本，`cn`为国服，`jp`为日服|

**未完待续**
