# dash-learn
Dash is an online tutorial to help you learn HTML, CSS, and JavaScript and create websites from scratch.

### dash教學翻譯

[官方網站](https://dash.generalassemb.ly/projects)

***

dash是一個html+css+js 之好玩又好有趣的學習網站。

優點： 互動性和回饋性很高，引發高度學習興趣。

缺點： 此教學網站以實作案例為教學方式，html+css+js的基礎觀念較不集中，建議可以先研究一下各語言彼此的用法與特性。

此文件只是個人學習的翻譯，要記得和教學網站搭配使用，直接看翻譯可能會有點不清楚，歡迎各位高手糾正與指教。

歡迎引用與分享 ：）
記得註明原出處就好。


###PROJECT 1: 

####BUILD A PERSONAL WEBSITE


	建立個人網站


1. Make the headline and inputs 

		新增標題和輸入框


2. Style the background and text 

		新增背景和文字樣式


3. Add a background image and logo

		增加背景圖片和logo


4. Build your own personal website

		建立你自己的個人網站



#####Make the headline and inputs 

Part1: HTML Basics

	單元1: 基本的HTML
	
	
投影片數量：29張


OUR MISSION:

	我們的任務：
	
Learn the basics of HTML while building a personal website for our friend Anna!

	建立個人網站給我們的朋友Anna，藉此學習基本的HTML。

The final design looks like this

	最後的設計畫面像這樣：

It looks like a lot to learn,but don't worry- we'll take it slow.

	看起來好像很多需要學習，但不用擔心！ 我們會循序漸進的實作 ：）

Here's what you'll do in Part 1:

	讓我們開始進入單元1。
	
As we go through the lesson,you'll write code in the text editor below and see the output in the preview on the right.

	透過我們的教程，你可以寫程式碼在左下方的文字編輯器（EDITOR），並且可以右方直接觀看程式碼的輸出結果(PREVIEW) 
	
Ready?

	你準備好了嗎？
	
LET'S GET STARTED

	讓我們一起開始吧！！
	
1. HTML Basics

        基本的HTML
	
HTML documents use <tags> to tell the browser how to format our content.

	HTML文件透過標籤（<tags>）來告訴瀏覽器如何顯示內容。


	例如： <h1>Anna</h1>

Opening tag- Everything after this becomes a first-level heading

	開始標籤- 使用“開始標籤“告訴瀏覽器，從這裡開始顯示第一字級的標題樣式。

Closing tag- The slash makes it a closing tag, ending the heading

	結束標籤- 結束標籤加上斜槓符號，使用“結束標籤“告訴瀏覽器，從這裡結束顯示第一字級的標題樣式。

To make a normal paragraph, the tag is <p>

	<p>是一般的文章標籤（tag）

Remember,it needs an opening and closing tag!

	請記得要記得加上開始和結束標籤。
	例如： <p>I'm Anna Su</p>
	
2. Email Form

		電子郵件表單
		
No matter what type of information you want from your users,to get it from them you'll need to use the<input> tag.


	無論你要從使用者獲得什麼類型的信息，你都要用<input>標籤。
	例如：<input type="email">
	上列這段程式碼，可以讓使用者輸入email，你將會獲得使用者的email資料。
	
There are many different types of inputs, but for now all we'll cover is "email" and "submit"

	然而inputs有很多種不同的類型，像是email和submit
	例如：<input type="email">或<input type="submit">
	
``<input type="email">``
	
This part is called an "attribute"

This is the attribute's value

	例如： <input type="email">
	其中type是input的屬性，email是type的屬性值。
	這段程式碼代表產生一個email的輸入框
	
The "email" input won't do much good without a "submit" button!

	如果有“email”的輸入框，那就一定要有“submit”的按鈕，才能讓使用者送出e-mail。
	
	例如：<input type="email">或<input type="submit">
	
Great! There's just one problem...

	很好！ 但現在剩下一個問題。
	
We don't actually say what users are supposed to type here.

	我們應該提示使用者，說明這個輸入框要輸入e-mail
	
Luckily,there is an attribute called placeholder that lets us add default text to our input,so users know what to type.  

``<input type="email" placeholder="Your email">``

	很幸運，有一個屬性叫做placeholder，加上這個屬性之後，可以在輸入框上顯示預設文字。
	用法：<input type="email" placeholder="請輸入您的e-mail">

In the next lesson,we'll learn how to add some style to our page with CSS!

	在下一堂課，我們將會學習到如何使用css來添加網頁的樣式。
	
總結：

這堂課學到

``h1-h6``

``email input``

``submit input``

``p``

``placeholder``

``style``

``body``

``head title``

***

程式碼如下：


<h1>Anna Su</h1>
<p>Hi! I'm Anna, I'm a F2E :)</p>
<input type="email" placeholder="Your email">
<input type="submit">


***

投影片數量：43張

Part 2: CSS Basics

	基本CSS
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. What CSS is,and how to add it to your site

2. How to structure your document properly

3. How to add common styles to your site

		我們的任務：
		在這堂課，我們將學到以下三點
		1. 什麼是CSS? 我們要如何把CSS加到你的網站裡
		2. 如何組織你的HTML架構
		3. 如何在你的網站中加入共用的樣式
		

This will get us even closer to the final design!

	我們最後的設計畫面像這樣：

LET'S GET STARTED

	讓我們一起開始吧！！
	
1. CSS Basics

		基本的CSS
		
WHAT IS HTML?

HTML is the structure of the content that goes inside the tags. Browsers provide default style,but it's pretty ugly by itself.

	HTML是什麼？ 
	HTML包含很多標籤（tags），這些標籤內容成為網頁的架構。
	瀏覽器提供標籤擁有各自預設的樣式，但預設樣式都很醜。
	例如：<input type="submit">  這是一段HTML語法，用來顯示一個按鈕，不同瀏覽器會給不同的預設樣式。未裝飾的預設樣式都不是很好看。

WHAT IS CSS?

CSS controls the style of the HTML content. It lets you change colors,fonts,layout,and more.

	CSS是什麼？
	CSS用來幫HTML的內容添加樣式。可以讓你改變顏色、字級、排版等等 


For small projects like this,the easiest way to add CSS to your HTML file is by using a ``<style>`` tag

* You could also include an external stylesheet, but we'll learn about that later.

		如果你只是要建立一個很小的專案，那你可以使用<style>這個標籤，簡單的將CSS樣式加到你的HTML檔案中。
		＊你也可以添加外部的樣式檔，稍後再為您講解此部分。
	
Write this in your `<style>` tag



    <style>
	  h1{
		text-align: center;
	  }
    </style>


QUICK TIP:

Be sure to include the line-breaks and tabs! These help make your code more readable.

	小祕訣： css語法中加上斷行和tab間距可以讓你的程式碼更易讀。
	
Let's take a closer look at the code you just wrote...

	讓我們仔細看看你剛剛寫的程式碼...

1. THE SELECTOR

This is where you choose which HTML elements you want to add style to. In this example,we select all the``<h1>``elements.


	1. 選擇器（Selector）
	如果我們想要針對<h1>這個HTML元素增加樣式，你必須在CSS內選擇指定的元素名稱，我們稱為選擇器。
	請參考下列的範例，此範例選擇<h1>這個元素。
	
``
h1{
	text-align: center;
}
``	

2. CURLY BRACKETS

All styles inside these will apply to the HTML elements chosen by the selector.

		2，大括號 

		括號內的所有樣式將套用到由選擇器選擇的HTML元素。

3. PROPERTY

A property controls one aspect of an HTML element's style,such as text-align,color,width,background,etc.

	3. 屬性

	加入屬性可以改變HTML元素的樣式，像是文字對齊的方向、顏色、寬度、背景圖片等等。
	
``
h1{
	text-align: center;
}
``

	例如： text-align就是css的屬性
	
3. VALUE

The value goes with the property. In this case,text-align's value could be left,right,center,or justify.


	3. 屬性值

	屬性後面加上屬性值。
	範例中text-align就是屬性，center就是屬性值。代表h1的文字要置中。text-align的屬性值包括left,right,center或justify，代表文字置左,文字置右,文字置中或文字左右對齊。
	
``
h1{
	text-align: center;
}
``

	例如： center就是css的屬性值


You can have multiple styles in the same ``<style>`` tag.

	你可以在<style>標籤內針對不同HTML元素設定很多樣式。
	請參考下方範例。


``
h1{
	text-align: center;
}
``


``p{
	text-align: center;
}``

That's cool,but if I want to make everything centered do I really need a new style for each individual element? Can't I just select them all at once?
	
	真酷！
	但我如果想要網頁內的所有元素都套用某些樣式，例如，網頁內的文字都垂直置中，那要怎麼做？	
	
Good question! We'll show you how to do that next.

	好問題！ 我們接下來將會告訴你該怎麼做。

2. Document Structure

		2. HTML文件結構
		
The best way to select all elements at once is to have a parent element that contains all the other elements.

Luckily,HTML gives us a tag called ``<body>`` that's explicitly designed for that purpose.

	最好的方法是選擇一個包含所有其他元素的父元素，幸運的是，HTML中有<body>這個標籤，包含網頁內的所有元素。

The<body>tag wraps around all the content that's displayed on the page.

	HTML的架構是將所有在網頁上顯示的內容放到<body>標籤內。

Now you can make one body style.

	現在你可以新增一個body的樣式如下。
``
body{
	text-align: center;
}``

...and the body style will affect all the elements inside the <body> tags!

	接著設定body的CSS樣式，將會套用在HTML內的所有元素。

Before body,we always start with another tag called <head>

It wraps around the ``<style>`` tag and othr elements that are nt content on the page itself,such as the ``<title>`` tag.

	再介紹一個HTML標籤，放在body之前，叫做<head>。

	<head>內放置一些資訊，像是<style><title>等。

Woo! Almost done with this part.
Just one more thing.

	哇！這個單元快結束了！但還有一件事情要注意！
	
To have a valid HTML document, we need to tell the browser we're using HTML5. It's easy to do:	
	
Just write <!DOCTYPE html> on the first line,before everything else.

That tells the browser we're using the newest version,HTML5.

	一個有效的HTML文件，必須要在html 最上行加上一段語法，讓瀏覽器知道這是HTML文件。
	而目前HTML最新的版本為HTML5，用法是加上<!DOCTYPE html>這段程式碼。
	
Together,the doctype,head,and body make up the basic foundation/structure that every website starts from.

Sometimes this is called "boilerplate"

	HTML的基本架構包含head,body如下：
	
	
	<!DOCTYPE html>
	  <head>
	  	<!-- Meta info goes here -->
	  </head>
	  <body>
	    <!-- Content goes here -->
	  </body>  
	
	
3. Common Styles

		3. 常見的樣式
	
Great job! Let's add a few more styles to the <body> before we wrap up.

	很好！我們來學習更多其他的樣式吧！
	
You can change the background's color using the background property.

The color property is for text.

``
body{
      background: black;
      color: white;
      font-family: helvetica;
    }
``

	你可以使用 background 這個屬性，用來改變背景顏色。
	例如： background: black; 設定背景為黑色。
	使用 color 這個屬性，用來改變字體顏色。
	例如： color: white; 設定文字顏色為白色。
	使用 font-family 這個屬性，用來改變字體的字型。
	例如： font-family: helvetica; 設定文字的字型為helvetica。


***

投影片數量：36張

Part 3: Images and form styling

	圖片和表格樣式
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. How to include the logo image

2. How to add a background image

3. How to style the email input form

		我們的任務：
		在這堂課，我們將學到以下三點
		1. 如何加入LOGO圖片
		2. 如何加入背景圖片
		3. 如何在email輸入表單加上樣式
		

At the end of this part your site will look like this!

	我們最後的設計畫面像這樣：

LET'S GET STARTED

	讓我們一起開始吧！！

1. Logo Image

		Logo圖片	

Adding an image is easy! Just use the <img> tag

	只要使用<img>這個標籤，就可以在你的網頁中加上圖片。
	<img src="/assets/anna.png">
	
The<img> tag uses the image located at the URL in the src attribute.

	<img>標籤中，有一個名稱為src的屬性，用來加上圖片的路徑。

Hrmm,"/assets/anna.png" doesn't look like a URL to me.
Don't URLs need a domain, like http://mysite.com,in them?

	恩..."/assets/anna.png"看起來不像網站圖片的路徑，為什麼這個路徑沒有網域名稱，像是這樣http://mysite.com
	
Good question! There are actually two types of URLs:
absolute and relative.

	好問題！事實上，路徑分為絕對路徑和相對路徑。
	
ABSOLUTE URL

http://dash.ga.co/assets/logo.png

Absolute URLs are the types of links you're used to. They include http:// and the full domain name before the directory(/assets/logo.png)

RELATIVE URL

/assets/logo.png

Relative URLs are shortcuts that allow you to skip the domain name.
It only works if you're linking to a file on the same domain as the current page.

	絕對路徑
	
	例如：http://dash.ga.co/assets/logo.png
	
	絕對路徑包括http://以及完整的網域名稱，最後加上圖片存放路徑。
	
	相對路徑
	
	例如：/assets/logo.png
	
	相對路徑比較簡短，省略http://以及完整的網域名稱，只要加上圖片存放路徑就可以正確顯示。
	
2. Background Image

		背景圖片	
		
Remember the background property from earlier?
We used it to make the body's background a color (black),but you can also use it to change the background to an image.

You can set the background to an image like this.
URL should be set to an actual path to an image file.

	記得在前面的課程裡有介紹background這個屬性，是用來設定背景圖片的顏色。然而，background這個屬性也可以用來設定背景圖片。用法如下，url屬性用來指定圖片路徑。
	
	body {
      background: url("http://dash.ga.co/assets/anna-bg.png");
    }
    
This is how you prevent the background from appearing "tiled".    

``background-size: cover;``

This will center the background image on the page.

``background-position: center;``

3. Form Styles

		3. 表單樣式
		
So far we've only applied styles to the <body> tag.
Let's get more specific and start applying styles to the other element.

Let's make the paragraph's font a little bigger.		
``p{
      font-size: 22px;
    }``
    
By setting border to 0,we can get rid of some of the default styling on our inputs.
``
input{
      border:0;
    }    ``


Padding is the amount of space beftween the edge of an element and the stuff inside it.

Let's even it out for both input elements and set it to 10 pixels.

``padding: 10px;``

Let's increase the font-size to make it more proportionate to the rest of the text.

`font-size: 18px;`

Almost done! Let's make the call-to-action button nice and bright red,then we'll be finished.

You can select an element by one of its attributes using square brackets,like this:


	input[type="submit"]{
      background: red;
      color: white;
    }

    
For example,you could select the email input using either input[type="email"] or input[placeholder="Your email"]
Both would work.

	像這個例子，你可以使用input[type="email"]這個語法來選擇輸入框這個樣式，或input[placeholder="Your email"]，這個語法可以針對placeholder內的文字來設定樣式。
	
	
***

投影片數量：28張

Part 1: Header HTML

	圖片和表格樣式
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. Set up the site's foundation

2. Make the header

3. Make the navigation links

		我們的任務：
		在這堂課，我們將學到以下三點
		1. 打造網站的基礎
		2. 建立標頭
		3. 建立導覽列連結
		
		
Here's the final design

	我們最後的設計畫面像這樣：

LET'S GET STARTED

	讓我們一起開始吧！！
	
	
1. Document Structure

		1. HTML文件架構

`
<!DOCTYPE html>
<head>
	<!-- Meta-info goes here -->
</head>
<body>
	<!-- Page content goes here -->
</body>
</html>
`

2. Header HTML

		2. HTML標頭
		
HTML5有提供一個標籤是<header>用來放HTML標頭的內容。

就像是<body>標籤是用來放HTML的所有內容。

一個基本的<header>內容，大概像下列這樣。

此範例的header包含一張圖片和一行標題。

`
<header>
	<img src="/assets/jeff.png">
	<h1>Anna's Blog</h1>
</header>
`	

3. Navigation

		3. 導覽列
		

導覽列通常使用`<ul>`這個標籤代表清單，`<ul>`是屬於沒有編號的列表。
`<ol>是`屬於有編號的列表。

例如-無編號的列表： 使用`<ul>`

<ul>
    <li><a href="#">About Me</a></li>
    <li><a href="#">Best Poems</a></li>
    <li><a href="#">Worst Poems</a></li>
</ul>


例如-有編號的列表： 使用`<ol>`
<ol>
    <li><a href="#">About Me</a></li>
    <li><a href="#">Best Poems</a></li>
    <li><a href="#">Worst Poems</a></li>
</ol>


`<ul>`和`<ol>` 裡面內容要放｀<li>｀標籤

如果導覽列需要連結，要記得加上`<a>`這個標籤

`<a>`這個標籤有一個`href`的屬性，用來放連結的URL

***



投影片數量：43張

Part 2: Header CSS

	標頭樣式
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. Add a CSS reset external CSS file

2. Style the navigation links

3. Style the rest of the header

		我們的任務：
		在這堂課，我們將學到以下三點
		1. 加入一個外部的css檔案，用來重置樣式
		2. 導覽列連結樣式
		3. 標頭部分樣式
		
		
This will get us even closer to the final design

	我們最後的設計畫面像這樣：

LET'S GET STARTED

	讓我們一起開始吧！！
	
	
1. CSS Reset

		1. 重置CSS樣式
		
之前的課程有說明，我們可以使用`<style>`這個標簽，讓我們可以在HTML裡面，增加樣式。

現在要介紹，我們還可以使用`<link>`來增加外部樣式。


例如在`<head>`這個標籤裡面加上：

`<link href="/normalize.css" rel="stylesheet">`

在html裡面，只需要加上一行code，就可以載入css程式碼。

href 用來設定css的存放路徑

rel 是告訴瀏覽器此連結是“stylesheet”樣式表

reader all elements more consistently and in line with modern standards


各個瀏覽器針對每個元素會預設不同的樣式，但客戶或使用者總是希望，無論你使用任何瀏覽器，都能讓你的網頁顯示效果更加一致。
而，為了解決這個問題，我們可以預先載入reset.css 或normalize.css。

1. Navigation Styles

		1. 導覽列樣式
		
例如： 瀏覽器會給列表預設的樣式，包含左邊的padding和圓點，導致清單沒有辦法置中。

display

block的元素預設包括header p li

inline預設包括a span

padding: top right bottom left

1. Header Styles

		1. 標頭樣式

在`<header>`標籤內增加樣式，例如：

```
header{
      text-align: center;
      background: url("http://dash.ga.co/assets/jeff-bg.png");
      background-size: cover;
      color: white;
    }
```

投影片數量：65張

Part 3: Responsive design & Javascript

	介紹響應式設計與Javascript
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. Give the content a responsive design

2. Learn about advanced colors

3. Make our own "like" button in Javascript

		我們的任務：
		在這堂課，我們將學到以下三點
		1. 建立響應式設計內容
		2. 學習設定顏色樣式的進階語法
		3. 使用Javascript語法來新增一個按鈕
		


LET'S GET STARTED

	讓我們一起開始吧！！
	
	
1. Responsive Design

		1. 響應式設計
		
		
響應式設計的是一種網站技術，是使用多種設備（桌機、平板、手機）都可以正常瀏覽的設計。。


為了實現響應式設計，我們必須學習一些CSS的技巧來達成這個目的。

我們可以使用media query來完成。

例如：

原本列表樣式是

`
    ul {
      padding: 10px;
      background: rgba(0,0,0,0.5);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
`    

再加一段：

`
@media (max-width: 500px){
      h1{
        font-size: 36px;
      }
      li{
        display: block;
        padding: 5px;
      }
    }
`    

如此一來就可以調整列表在不同設備所顯示的內容。

html:


`
  <article>
    <h2>Sartorial synth Echo Park, roof party</h2>
    <p>chambray you probably haven't heard of them pour-over viral selvage umami skateboard VHS post-ironic selfies. Wes Anderson gentrify fanny pack twee, bicycle rights bitters blog keffiyeh plaid flannel. Tonx irony cliche sustainable mlkshk bitters. Four loko leggings chambray Vice.</p>
  </article>
`  
  
css:
`
article {
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
    }
`    


`margin: 0 atuo; `  內容置中

`max-width: 500px; `  最小寬度


2.Advanced Colors

		1. 進階的顏色語法
		
設定顏色的樣式包括關鍵字，十六進位的顏色，或rgba。

1.關鍵字
	
	white,black,red
	
例如：`background: red;`


2.rgb (16進位)

我們也可以使用Hex Color Code like this:

`#red green blue`

`#F00`

	這邊的F 等於 100% red
	
例如：

`background: #F00;`	
	
it ranges from 0 to F

`#000`  black
`#FFF` white
`#F00` red

3.rgba (16進位+alpha)

alpha = transparency = 透明度

	rgba(255,255,255,1)

例如：

`background: rgba(0,0,0,0.5);`


3.Javascript!

		1.Javascript!
		

首先，我們先在HTML裡面加上按鈕，語法如下

`<button>Like</button>`

接著我們要加上javascript語法

如果我們要在html裡面加上javascript，

我們可以使用`<script>`這個標籤。


例如：

`<script>
alert("Javascript works!");
</script>
`

jQuery:

`
$("button").on("click",function()){
	alert("clicked")
});
`

***

PROJECT 3: BUILD A SMALL BUSINESS WEBSITE

	建立一個小型的商業網站


1. Position images & text 

2. Add webfonts and color fades 

3. Make it mobile and interactive


投影片數量：81張

Part 1: Classes,divs & CSS positioning

	樣式，區塊與css位置
	
OUR MISSION: In this lesson, we'll learn 3 new things:

1. Creative ways to use background images

2. How to group and position multiple elements with CSS


		我們的任務：
		在這堂課，我們將學到以下三點
		1. 背景圖片
		2. 如何設定多組元素的CSS
		


LET'S GET STARTED

	讓我們一起開始吧！！
	
	
1. Visuals

		視覺
	
什麼是DIV?

  `<div>`是一種無語義的標籤，
  
  有語義標簽包括`<article>` `<header>` `<nav>` `<fotter>`。等。

`background-size: cover;`

`margin: 0 auto;`

這邊不用寫單位，例如： 0px

因為0就是0，不需要特別指定單位。
0 in= 0 cm = 0ft



	


