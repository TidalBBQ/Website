# HTML
HTML超文本標記語言(**H**yper **T**ext **M**arkup **L**anguage)\
透過標籤的方式來呈現網頁\
例如:
```html
<p>我的第一個網頁</p>
```
## 常見且常用的標籤
- h1~h6\
   **h1**為最大的依序遞減下去至**h6**
   
- 表單(form)\
  表單用於把使用者輸入的資料收集起來\
  有許多種輸入方法
  - 文字方塊
  - 單/多選項按鈕
- 表格(table)
  表格可以把資料用更方正的方式呈現
	<table>
		<thead>
			<tr>
				<th>表格上方</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>表格內容</td>
			</tr>
			<tr>
				<td>表格下方</td>
			</tr>
		</tbody>
	</table>
- 區塊(div)\
    被div標籤包起來的區域是被獨立或是切割出來的一部分\
    div標籤通常配合著CSS或是JavaScript一起使用
- 列表(ul、li)\
	`<ul>`是無排序規則的列表，像是這篇文章的排序方式
    >`<li>`則是將要顯示的內容包起來的標籤
## HTML 事件(DOM Events)
- Anchor
- Document
- Event
- Form、Input
- Frame、Framset、IFrame
- Image
- Location
- Navigator
- Option、Select
- Screen
- Table
- Window
## 引入JavaScript以及CSS
`<script>...</script>`\
`<style>...</style`
## HTML與XHTML差異
- XHTML標籤需要有先後順序
>`<b><i>...</b></i>`\
>`<b><i>....</i></b>`
- XHTML標籤必須要成對

>`<p>...</p>`
- 空白標籤也需要有結束標籤
>`...<br />`
- XHTML標籤內文字必須小寫
>`<p>...</p>`
- XHTML中必須要擁有一個根標籤(HTML)
>```
><html>
><head>...</head>
><body>...</body>
></html>
>```
- XHTML屬性名稱必須小寫
`<font font-size="10px">`
- XHTML屬性值必須加上引號\
`<font font-szie="10px">`
- XHTML屬性不能簡寫
`<input checked>`\
`<input checked="checked"`
- 強制在開頭加上<!DOCTYPE>
>一個XHTML有三個主要的部份
>>- DOCTYPE
>>- Head
>>- Body
		
