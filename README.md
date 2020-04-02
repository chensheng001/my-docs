# 文档官网

## 运行预览

```javascript
npm install
npm run dev
```

或者

```javascript
yarn install
yarn run dev
```

打开：http://localhost:5002/#sort=sys&doc=chapter/main.md

## 关于编辑内容
    直接编辑 /docs/sys/chapter/main.md 文件即可，需遵循markdown语法

##  markdown语法举例：
```html
    ## 代码块 
    ```html
    <h1>Hello World</h1>
    ```  
    `  console.log("hello world") `


    ## a链接
    这是一个链接 [测试](https://www.baidu.com)

    ## 段落 段落的换行是使用两个以上空格加上回车
    aaaaaaaaaaaaaa  
    bbbbbbbbbbbbbbb

    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题

    ## 区块
    > 学的不仅是技术更是梦想

    ## 列表
    * 第一项
    * 第二项
    * 第三项

    ## 表格

    | 参数 | 说明 | 类型| 可选值| 默认值|
    | --- | --- | --- | --- | --- |
    | `disabled` | 是否禁用 | Boolean | true / false | false |
    | `size` | 预设输入框尺寸 | String | `l`, `m`, `s` | `m` |
    | `color` | 输入框类型 | String | `primary`, `white` | `primary` |
```