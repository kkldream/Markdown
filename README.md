# 目錄
* [換行](#換行)
* [標題](#標題)
* [橫線](#橫線)
* [文本塊](#文本塊)
* [文字高亮](#文字高亮)
* [斜體、粗體、删除線](#斜體、粗體、删除線)
* [列表](#列表)
    * [無序列表](##無序列表)
    * [多級有序列表](##多級有序列表)
    * [複選框列表](##複選框列表)
* [多級結構](#多級結構)
* [連結](#連結)
    * [文章內跳到標題](#文章內跳到標題-ex連結連結)
    * [跳到本倉庫其他位置](#跳到本倉庫其他位置-eximg1imageimg1png)
    * [點擊圖片跳轉](#點擊圖片跳轉)
* [圖片](#圖片)
* [表格](#表格)
* [代碼高亮](#代碼高亮)
* [diff語法](#diff語法)
* [參考連結](#參考連結)

# 換行
直接回車不能換行，  
可以在上一行文本後面補兩個空格，  
這樣下一行的文本就換行了。

或者就是在兩行文本直接加一個空行。

也能實現換行效果，不過這個行間距有點大。

# 標題
    # 一級标題
    ## 二級标題
    ### 三級标題
    #### 四級标題
    ##### 五級标題
    ###### 六級标題

# 橫線
***、---、___可以顯示橫線效果

# 文本塊
    歡迎到訪
    很高興見到您
    
在連續幾行的文本開頭加入1個Tab或者4個空格  
或使用一對各三個的反引号，如下

    ```
    歡迎到訪
    很高興見到您
    ```

# 文字高亮
`linux` `網絡編程` `socket` `epoll`

    `linux` `網絡編程` `socket` `epoll` 

# 斜體、粗體、删除線
|語法|效果|
|----|-----|
|`*斜體1*`|*斜體1*|
|`_斜體2_`| _斜體2_|
|`**粗體1**`|**粗體1**|
|`__粗體2__`|__粗體2__|
|`這是一個 ~~删除線~~`|這是一個 ~~删除線~~|
|`***斜粗體1***`|***斜粗體1***|
|`___斜粗體2___`|___斜粗體2___|
|`***~~斜粗體删除線1~~***`|***~~斜粗體删除線1~~***|
|`~~***斜粗體删除線2***~~`|~~***斜粗體删除線2***~~|

# 列表
## 無序列表
* 昵稱：果凍蝦仁
* 昵稱：果凍蝦仁
- 别名：隔壁老王
- 别名：隔壁老王
* 編程語言
    * 腳本語言
        * Python
```
* 昵稱：果凍蝦仁
* 昵稱：果凍蝦仁
- 别名：隔壁老王
- 别名：隔壁老王
* 編程語言
    * 腳本語言
        * Python
```
## 多級有序列表
1. 這是一級的有序列表，數字1還是1
   1. 這是二級的有序列表，阿拉伯數字在顯示的時候變成了羅馬數字
      1. 這是三級的有序列表，數字在顯示的時候變成了英文字母
```
1. 這是一級的有序列表，數字1還是1
   1. 這是二級的有序列表，阿拉伯數字在顯示的時候變成了羅馬數字
      1. 這是三級的有序列表，數字在顯示的時候變成了英文字母
```
## 複選框列表
- [x] 需求分析
- [x] 系統設計
- [x] 詳細設計
- [ ] 編碼
- [ ] 測試
- [ ] 交付
```
- [x] 需求分析
- [x] 系統設計
- [x] 詳細設計
- [ ] 編碼
- [ ] 測試
- [ ] 交付
```
# 多級結構
> 數據結構
>> 樹
>>> 二叉樹
>>>> 平衡二叉樹
>>>>> 滿二叉樹

    > 數據結構
    >> 樹
    >>> 二叉樹
    >>>> 平衡二叉樹
    >>>>> 滿二叉樹

# 連結
www.google.com  
[Google](www.google.com)

    直接打網址
    [說明文字](網址)

### 文章內跳到標題 ex：[連結](#連結)

    [標題](#連結)
連結中只能使用`文字`、`減號(-)`、`底線(_)`，其中`空格`由`-`取代  
其餘都省略，ex：`/` `(` `)` `?` `!` `@` `#` `$` `%` `^` `&` `*` `+` `~` `[` `]` `{` `}` `<` `>` `=` `：` `，` `。`等

### 跳到本倉庫其他位置 ex：[img1](./image/img1.png)

    [相對路徑](./image/img1.png)
    [絕對路徑](/Markdown/image/img1.png)

### 點擊圖片跳轉

    [![說明文字](顯示圖片)](跳轉路徑)

# 圖片

![img1_text](image/img1.png)

    ![說明文字](網址或路徑)

# 表格
| 左對齊(預設)| 右對齊 | 居中對齊 |
| :-| -: | :-: |
| 單元格 | 單元格 | 單元格 |
| 單元格 | 單元格 | 單元格 |

    | 左對齊(預設) | 右對齊 | 居中對齊 |
    | :-----| ----: | :----: |
    | 單元格 | 單元格 | 單元格 |
    | 單元格 | 單元格 | 單元格 |

# 代碼高亮
```java
public static void main(String[]args){} //Java
```

    ```java
    public static void main(String[]args){} //Java
    ```

# diff語法
其語法與代碼高亮類似，隻是在三個反引号後面寫diff， 并且其内容中，可以用 + 開頭表示新增，- 開頭表示删除。 另外還有有 !和#的語法。
```diff
+ 人閑桂花落，
- 夜靜春山空。
! 月出驚山鳥，
# 時鳴春澗中。
```
    ```diff
    + 人閑桂花落，
    - 夜靜春山空。
    ! 月出驚山鳥，
    # 時鳴春澗中。
    ```

# 參考連結
https://ithelp.ithome.com.tw/articles/10203758

https://github.com/guodongxiaren/README#%E5%88%97%E8%A1%A8
