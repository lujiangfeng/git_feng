# 如何在VSCode中开发Python程序 和 写 Markdown文档

## 1. VSCode 中 Python 插件

1. Chinese：汉化
2. python：python 必须的
3. Markdown All in One：Markdown 文档
4. Markdown Preview Github Styling：Github Markdown 风格
5. vscode-icons：美化图标
6. Anaconda Extension Pack：Conda 必须的
7. Path Intellisense：感知路径

## 2. VSCode 技巧

1. 在setting.json中，加上 `"python.autoComplete.addBrackets": true,`可以让你在print的时候，自动那个带上括号；
2. pip install autopep8,遵循pep8代码规范。

## 3. 使用VSCode 编写 MarkDown 文档

1. 标题
   以#的数量来算，正文不需要#

2. 代码编写

    ```python
    print('hello')
    ```

    行内代码： `print('hello')`

3. 有序列表

   1. 天
   2. 王
   3. 盖
   4. 地
   5. 虎

4. 无序列表

   - 天
   - 王
   - 盖
   - 地
   - 虎
  
5. 超链接

    [如何简单形象又有趣地讲解神经网络是什么？ - 王小龙的回答 - 知乎](https://www.zhihu.com/question/22553761/answer/36429105)

6. 图片

    如果学会了以上超链接的写法，那么添加图片就很简单了，只要在之前的写法前面加上 ! 就可以了。

7. 数学公式

    这里用$$ 你的公式:z=wx+b $$ 来写，效果如下：
    $$ 你的公式:z=wx+b $$

8. 注释

    注释在文档预览中，是看不到的，注释要用Crtl+/

## 4. VSCOde Markdown 写作注意点

1. 文章开头必须要有 #，即一级标题，否则提示：MD041/first-line-heading/first-line-h1: First line in file should be a top level headingmarkdownlint(MD041)；
   
2. 文章标题按照大小排列，不能从一级标题跳到三级标题，否则提示：MD001 - Heading levels should only increment by one level at a time；

3. 大标题下面空一行再写东西，否则提示：MD022/blanks-around-headings/blanks-around-headers: Headings should be surrounded by blank lines [Expected: 1; Actual: 0; Below]markdownlint(MD022)；

4. 列表之间无须换行，列表和字列表之间无须换行,但建议换行；

5. 列表下面，无字列表的时候，要换行写东西，否则会合并成一行。
