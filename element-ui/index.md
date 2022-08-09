---
marp: true
paginate: true
footer: '徐堂鑫 2022-07-15'
style: 
---
![bg fit blur:4px](./imgs/pic1.png)
## 浅谈element ui 组件库
* element 项目结构
* 如何支持自定义主题的
* Vue.use()
* 如何做到按需引入的
* 依赖了哪些第三方库
* 以button组件和avatar组件为例 感受element ui的编码风格
---
#### github地址：https://github.com/ElemeFE/element
![h:400px](./imgs/pic2.png)

---
#### 项目结构：
![bg h:400px right](./imgs/pic3.png)
- build webpack编译配置文件目录
- examples element ui官方主页项目目录
- packages 各个组件的源码目录
- src 项目使用到的公共指令、工具集等源码存放目录
- test 单元测试相关
- type typescript相关文件包


---
## element ui 如何支持自定义主题的?
* element-ui 组件的样式、公共样式都在 packages/theme-chalk 文件中
* element-ui 组件样式中的颜色、字体、线条等等样式都是通过变量的方式引入的
* 只要修改这些变量，就可以方便地实现组件的主题改变
---
![fit](./imgs/pic4.png)

---
---
---
---
---
---
---
---
---
