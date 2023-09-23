Markdown語法：

換行：需在最後面+兩個空白鍵  
行末按兩個空格  産生斷行

	[Tab]縮排
	理
文字格式：
斜體：在文字兩邊加上一個 * 或是一個 _  
  *星號* 或是 _底線_  
  `*星號*`

  ~~兩個波浪~~
- 連結：以方括號括住連結文字 (例如 [Google 文件])。
在連結文字後面加上連結網址並以圓括號括住
在 [Google 文件](https://docs.google.com/document/)中開啟檔案。
`[Google 文件](https://docs.google.com/document/)`
注意：方括號與圓括號之間不得有空格

> 引言
`> 引言`

6 種不同的標題：
# 標題1
## 標題2
### 標題3
#### 標題4
##### 標題5
###### 標題6

清單
清單分為一般列表及包含數字符號的列表，兩種都包含多個層級，只要加上一個縮排或兩個空格就可以新增一個層級。

一般列表的使用彈性較高，-、+、* 等符號後方加上一個空白後都可以轉為列表，要表示下一個層級可多一個縮排或是兩個空白即可
有序列表: 直接打 `數字`+ `.` + `空白鍵`
1. 有序列表1
2. 有序列表2
	1. 子有序列表1
	2. 子有序列表2
2. two
5. test
6.

- 無序清單
- 無序清單
    - 無序清單子清單
        - 無序清單子子清單

也可以使用星號 * 或 加號 +


* 連結兩邊加上`<` `>`就會產生超連結
<http://dillinger.io/>

* 名稱兩邊加上`[` `]`然後再連結兩邊加上`(` `)`就可以將連結替換成文字連結
[Dillinger](http://dillinger.io/ "link")

* 將`[` `]`前+`!`，則可以產生圖片 (把滑鼠指向圖片可以看到註解）

	![圖片參考名稱](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo")


- 行內的 `程式碼` 用 `反引號` 包起來
輸出具有 Highlight 的程式碼
- 區塊的 `程式碼` 用 ```三個反引號```包起來
記得要加上語言名稱
```Python
	print(f"test")
```

*斜體字*
**粗體字**
***斜體兼粗體***
~~刪除線~~

<input type="checkbox" checked> some checked text

<input type="checkbox"> some unchecked text (checked)

You are using HTML tags instead of markdown text like - [x] or - [ ]
🔵 ✅ ⬜

- [ ] Unchecked
- [x] Checked
Markdown Checkboxes (Matt Bierner)

    就會輸出 套件管理工具 pip 的版本, 例如：
    pip 23.1.2 from C:\Software\Python\Python311\Lib\site-packages\pip (python 3.11)
    或 (在Anaconda Prompt 終端機內)
    pip 23.2.1 from C:\Software\anaconda3\Lib\site-packages\pip (python 3.11)

    - 提醒：
        在許多文章中安裝指令 會像 **`py -m** pip --version` 或 **`python -m** pip --version`
        因為新手都用較新版本的 Python，沒有舊Python版本的考慮，所以在 pip 指令前，我認為不需要加上 `py-m` 或 `python -m`

- 在Anaconda Prompt 終端機 輸入命令列(CLI)的指令：

    `conda --version`

編輯軟體不支援上標、下標語法，可以改用 HTML 的語法
LaTex數學符號

$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or

Markdown支援在下面這些符號前面加上反斜線來幫助插入普通的符號：

\\   反斜線
\`   反引號
*   星號 *  
_   底線  
{}  大括號    
[]  方括號  
()  括號  
\#   井字號 #    
\+   加號  
\-   減號-  
.   英文句點.  
!   驚嘆號  

- `Ctrl + Shift + \``    

Press `Ctrl + Shift + \` to activate the command.


$$
單行數學式 y = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

行內數學式 $y = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

引用區塊是以 > 開頭，可以每一行都加上 >，或是只有第一行都加上 >，接下來在遇到空行之前的文字都在引用區塊的範圍內。

> 引用區塊第1行
引用區塊第2行
引用區塊第3行


<details>
  <summary>點選展開!</summary>

  1. 摺疊內容
  2. *斜體字*
      - **粗體字**
      - `強調`樣式
</details>

<details open>
  <summary>Click to expand!</summary>

  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>

<details open>
  <summary><i>Wow, so fancy</i></summary>
  <b>WOW, SO BOLD</b>
</details>

<details open>
  <summary>Hello</summary>
  World!
</details>

<details><h3><summary>This is an h2 title</summary></h3>
Content goes here.
</details>

<details>
  <summary>
    <h2>
      Title
    </h2>
  </summary>
  content
</details>

```
 using the <details> and <summary> HTML tags to create a collapsible section. This is how it works:

The <details> tag is used to create an interactive widget that the user can open or close. Any content within this tag will be hidden by default, but can be revealed by the user.
The <summary> tag is used to specify the visible heading for the collapsible content. The text within the <summary> tags will always be visible and clicking on it will reveal or hide the rest of the content.

<details>
  <summary>Hello</summary>
  World!
</details>

<details>
  <summary>Hello</summary>
  **WOW, SO BOLD**
</details>

Make sure you have an empty line after the closing </summary> tag, otherwise the markdown/code blocks won't show correctly.

Make sure you have an empty line after the closing </details> tag if you have multiple collapsible sections.

```