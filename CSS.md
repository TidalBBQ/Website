# CSS
CSS指的是階層樣式表(**C**ascading **S**tyle **S**heets)
樣式定義如何顯示HTML的相關元素
樣式通常都儲存在外部樣式表中
外部樣式表通常儲存在CSS資料夾中
## CSS語法
  ```
  p {
    color:red;
    text-align:center;
  }
  ```
先定義要修改的元素如:p, table...等\
每一行定義一個屬性和一個值，中間要以冒號間隔\
每一行定義完之後都要以分號結尾\
CSS的註解如同PHP一樣`/*...*/`
## CSS 選擇器
在HTML中要設置CSS樣式，需要先設置**id**、**class**選擇器
- id選擇器
HTML屬性中設置id，需要在CSS欲修改的元素前以 **#** 定義
  ```
  #name  {
      font-size:15px;
  }
  ```
- class選擇器
不同於id的地方只有定義的方式以及可以指定HTML元素使用\
class選擇器要以 **.** 定義
  ```
  form.user {
    text-align:center;
  }
  ``` 
## CSS建立
總共有三種插入樣式的方法
- 外部樣式表\
利用<link>標籤連接到樣式表所在檔案\
  `<link rel="stylesheet" type="text/css" href="style.css">`
- 內部樣式表\
將CSS定義在<head>標籤內
  ```
  <head>
    <style>
        ....
    </style>
  </head>
  ```
- 內嵌樣式\
直接將CSS跟內容混雜在一起十分不建議使用\
`<p style="color=#F5F5F5;margin-right:10px">...</p>`
## 一定要熟悉的樣式
- padding、margin\
  ![Imgur](https://i.imgur.com/jc8zu7L.png)\
  - padding\
    `padding:上 右 下 左;` `padding:上下 左右;` `padding:上 左右 下;` `padding:四個邊同樣値;`\
    padding可以去修改上內距、右內距、下內距與左內距，每個值必須用半形空白隔開，必須注意的是內距不能為負值
    ### padding獨立寫法
      - padding-top
      - padding-right
      - padding-bottom
      - padding-left
    ### padding可定義的值
      - padding:auto  讓瀏覽器自行設定
      - padding:長度單位 單位可以是em、px、pt等
      - padding:% 讓瀏覽器依照%數自行設定
  - margin\
    `margin:上 右 下 左;`　`margin:上下 左右;`　`margin:上 左右 下;`　`margin:四個邊同樣値;`\
    margin可以去修改上外距、右外距、下外距與左外距，每個值必須用半形空白隔開，外距可以為負值\
    margin 也可以像padding一樣有獨立寫法
    ### margin獨立寫法
      - margin-top
      - margin-right
      - margin-bottom
      - margin-left
    ### margin 
      - margin:auto  讓瀏覽器自行設定
      - margin:長度單位 單位可以是em、px、pt等
      - margin:% 讓瀏覽器依照%數自行設定   
