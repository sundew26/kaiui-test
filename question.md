1. searchbar， toast组件内部引用icon组件方式@components有误（../）
3. toast
  1. toast消失 console.log输出弹窗关闭
  2. 案例组件引用问题
  3. 组件首页为toast轻提示 文档为toast提示
  4. demo里 loading 旋转的时候没有固定位置，有点飘
  5. demo种类少，没有把所有类型都列出来
4. numberpicker 数字输入框
  1. 样式不太好看
  2. 输入框会出现为空的情况(全选，粘贴，输入框为空)
  3. 文档案例中组件引用问题，import NumberPicker from '@/components/NumberPicker'
  4. demo 大中小样式都应该列出来
5. actionsheet 
  1. wxParse冗余报错
  2. 案例组件引用问题
6. searchbar 
  1. 点击匹配出的文案 搜索框文案不变
  2. 匹配很多的时候，往下滑动，搜索框没有固定(或者控制匹配列表高度)
  3. 文档引用组件不对：import Searchbar from 'kai-ui/Searchbar' 应为：import Searchbar from 'kai-ui/SearchBar'
7. input输入框，文档里标题为input框，不一致
8.  Switch 开关 文档中component引用没对齐
9.  radio文档 代码文案没有对齐
10. select demo最好分类展示
11. dialog demo里loading旋转时有点飘
12. toptips 案例 组件引用问题
13. tab文档里概述：适用于分类类信息展示（不知道有没有问题）
14. popup 案例组件引用问题
15. tag 案例组件引用
16. loadmore 
  1.  案例组件引用
  2.  loading旋转太慢
18. icon 
  1.  案例组件引用
  2.  能分类展示更好
19. grid demo里 图标文字可以稍微调整下





整体：
1. 文档案例中排版
2. console.log() 是否去除，或者加上有意义的前置
3. 展示类组件，文档都写的`@import '../node_modules/kai-ui/src/less/index';`，全局引用样式是否会更好：`<style lang="less" src="../node_modules/kai-ui/src/less/index.less"></style>`
4. 文档不够详细
5. wp的demo里内容尽量丰富一点，把各种情况都列出来。

stardew:
1. icon 案例里组件引用方式要改下
2. popup 案例里<style lang="less" src="./index.less"></style>是否最好去掉？
3. popup 左弹出关闭动画有点问题
4. popup 没对 events 里 pop 事件描述说明
5. tag： type 参数有哪些选项没有说明
6. tab： 缺少 doInitTabData 事件的说明
7. tab： 参数说明里 bindchange 应改为 bindChange
8. select： selectData 里可以配置event，参数里没说明；
    另 select-item 事件没有描述说明；
9. switch: 组件引用命名不能使用保留字 switch
10. actionsheet：wxParse相关代码要删除，包括文档案例里写的哟
    



[Error] {"message":"Unexpected token: operator (>)","filename":0,"line":128,"col":39,"pos":3965}

class需要大写


wx5ceeaea855a29b5e