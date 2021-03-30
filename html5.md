To know about html5 on browser support(all browsers): 

http://html5test.com/index.html

To know about scaling of the screen:

https://bluetree.ai/screenfly/?u=https%3A//github.com&a=5



## 
    <!DOCTYPE html> 
   **Explaination**: The <!DOCTYPE html> declaration is used to inform a website visitor's browser that the document being rendered is an HTML document.

Read more: https://html.com/tags/doctype/#ixzz6qWK5EEh6

##  
    <title>
        Document Title
    </title>
    
   **Explaination**: Inside Google search results, each page entry is shown with the title, should be carefully chosen and while bookmarking title comes as as bookmark name.
   
##
  Basic Document structure: 
    
    <!DOCTYPE html>
    <html>
      <head>
        <title>
            Document Title
        </title>
    </head>
    <body>
    </body>
  </html>
  
##
  information which put under head section generally used by search engines.
  
## 
 Logical Division done by div:
 
    <!DOCTYPE html>
    <html>
      <head>
        <title>
          Document Title
        </title>
      </head>
      <body>
        <div id='intro'>
          <h1> My First div.</h1>
          <p> My first div created.</p>
        </div>
      </body>
    </html>
    
    
## 

 p tag:
 
  <!DOCTYPE html>
    <html>
      <head>
        <title>
          Document Title
        </title>
      </head>
      <body>
        <p> I live in Pune. I am an intermediate professional in frontend programming. I had learnt html5 and css3 in 2018</p>
      </body>
    </html>

##
 
 break tag:
 
  <!DOCTYPE html>
    <html>
      <head>
        <title>
          Document Title
        </title>
      </head>
      <body>
        <p> I live in Pune. <br/> I am an intermediate professional in frontend programming.<br/> I had learnt html5 and css3 in 2018</p>
      </body>
     </html
 
## 

preformatted tags: this is used to preserve spaces while rendering  html.

  <!DOCTYPE html>
    <html>
      <head>
        <title>
          Document Title
        </title>
      </head>
      <body>
        <p>
          <pre>
            I live in Pune.         I am an intermediate professional in frontend programming.          I had learnt html5 and css3 in 2018
          </pre>
         </p>
      </body>
    </html>

##
 Attributes: 
  - class
  - id
  - name
  
##
  
  type in ordered and unordered list:
  
      <!DOCTYPE html>
        <html>
          <head>
            <title>My first Html Document</title>
          </head>
          <body>
            <h1> All about Mark Lassoff .....</h1>
            <p>My Favorite Bands</p>
            <ul type="Disc">
              <li>Journey</li>
              <li>REO Speedwagon</li>
              <li>Heart</li>
              <li>Foreigner</li>
              <li>The Cure</li>
            </ul>
            <p>My Favorite Foods</p>
            <ol type="1" start="3">
              <li>Spaghetti</li>
              <li>Hamburgers</li>
              <li>Hot Dogs</li>
              <li>Shellfish</li>
            </ol>
          </body>
        </html>
        
        
        
##

  blockquote and citation:
 
    <blockquote cite="https://www.worldwildlife.org/about">
        For 60 years, WWF has worked to help people and nature thrive.

        As the world’s leading conservation organization, WWF works in nearly 100 countries. At every level, we
        collaborate with people around the world to develop and deliver innovative solutions that protect communities,
        wildlife, and the places in which they live.
    </blockquote>
    
## 
 Formatting bold and strong:
 
 em: Italic
 strong: Bold
 del: to show in deleted formatted.
 mark: to mark the text in yellow format.
 ins: to mark the text in underline format.
 
 
      <!DOCTYPE html>
        <html>
          <head>
            <title>My first Html Document</title>
          </head>
          <body>
            <p>The quick brown<em>fox jumped over the lazy dogs.</em></p>
            <p><strong>The quick brown</strong> fox jumped over the lazy dogs.</p>
            <p><ins>The quick brown</ins> fox jumped over the lazy dogs.</p>
          </body>
        </html>
        
        
 ## 
 
  how to print html tags in html5:
  
    <code> &lt;p&gt;Hello World! &lt;/p&gt;</code>
   
##

How to show link a youtube video on your website: 

Open your video on youtube. click on share button it will give you embed url, copy and paste in your html.

  <!DOCTYPE html>
    <html>
      <head>
        <title> Linking</title>
      </head>
      <body>
       see a video <a href="http://youtube.com">youtube</a>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/D6xkbGLQesk" title="YouTube video player"
        frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
      </body>
    </html>
    
    
##

target attribute:

  to load a new page or external url in a new window: 
    
     <a target="_blank" href="http://google.com"> </a>
    
  to load a new page on the current window:
  
     <a target="_self" href="http://google.com"></a>
     
     
##

to move through a long document, index is created.

    <a name="top">
     <p> this is a long document , lets enable indexing on the page </p>
    </a>
   
    <a href="#top"> move to top <a>
    
    
##

 why to add alt tag on images:
    it is a description of the image.
    It gives idea to visually impaired people about the image. but they cant see it.
   Search engines like google, when page is indexed. it gives a better idea them to search.
  
## 

Working with tables:

<table border="1" cellspacing="0" cellpadding="3">
cellspacing set to 0 to remove spacing created by borders of the cell.
cellpadding is set to have some space in a cell around text.
    
    
   alternate in css:
   
   table, tr, td {
    border: 2px solid black;
    border-collapse: collapse;
   }
   
##

caption can be provided to the table, to show about the table.

<table><caption>My table </caption> </table>

##

Define a form on the web page: 

   <form action="#" method="POST">
    
   </form>
   
   
   action  can be a method which can save data of the form and method is GET/POST.
  
    <input type="text" required> 
    
    required is used to have some value in this input.
    
    <input type="text" max-length="5">
    
    max-length is to limit the input value to 5 chars.
    
    <input type="text" placeholder="Enter your name">
    
##    
    
how to group controls on a form

  <form action="#" method="POST">
        <fieldset>
            <legend>Personal information</legend>
            <label for="first">First</label>
            <input type="text" id="first" name="first" />
            <br />
            <label for="last">Last</label>
            <input type="text" id="last" name="last" />
            <br />
            <label for="last">Email</label>
            <input type="email" id="last" name="last" required />
        </fieldset>
    </form>
    
## 

Google bot is Google's crawling bot.
site map is needed to help google bot for intelligently crawling through your website.

more info: https://developers.google.com/search/docs/guides/get-started


##

 link rel vs script src
 
 stylesheet references are to go with link rel and script src is to have executable javascript reference.
 
 https://stackoverflow.com/questions/12178429/whats-the-difference-between-using-link-and-script-tag-to-reference-javascript
 
 ##

 HTML5 API (Applicatipn Programming Interface)
  - Drag and Drop
  - Web Workers
  - Web storage api
  - web Sockets
  - Media api
  - GeoLocation api

##

Playing with Canvas

    <!DOCTYPE html>
    <html>
        <head>
            <title>Canvas</title>
            <style>
                #myCanvas {
                    background-color: aqua;
                }
            </style>
            <script>
                window.onload = function () {
                    var canvas = document.getElementById('myCanvas');
                    if (canvas.getContext) {
                    var ctx = canvas.getContext("2d")
                    ctx.strokeStyle = "green"
                    ctx.fillStyle = "green"
                    ctx.strokeRect(50, 50, 100, 100)
                    ctx.fillRect(200, 50, 100, 100)
                    ctx.rect(350, 50, 100, 100)
                    ctx.stroke();
                    }
                }
            </script>
        </head>
        <body>
            <canvas id="myCanvas" width="400" height="500"></canvas>
        </body>
     </html>


More info: http://falcon80.com/HTMLCanvas/TextManipulation/AddText.html

 ## 
 
 CSS box model: 
 
   -> margin
     -> border
        -> padding
            -> actual element
            
            
 ##
 
 page layout
 
 <div id="content"> 
    <header> header div </header>
    <div id="content1"> </div>
    <div id="content2"> </div>
    <div id="content3"> </div>
    <footer> footer div</footer>
</div>


## 

to design responsive stylesheet:
 http://getskeleton.com/
