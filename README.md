<!doctype html>
<html>
<head>
  <title>WEB1 - html</title>
  <meta charset="utf-8">
  <style>
    a {
      color:black;
      text-decoration: none;
    }
    h1{
      font-size: 45px;
      text-align: center;
      border-bottom: 1px solid gray;
      margin:0px;
      padding: 20px;
    }
    #grid ol{
      border-right: 1px solid gray;
      width: 100px;
      margin: 0px;
      padding: 20px;
      padding-left: 32px;
    }
    body{
      margin: 0px;
    }
    #grid{
      display: grid;
      grid-template-columns: 150px 1fr;
    }
    #main{
      padding-left: 20px;
    }
  </style>
</head>
<body>
  <h1><a href="1.html">  God & King Proje</a></h1>

<div id = "grid">
  <ol>
    <li> <a href ="2.html">JAVA</a></li>
    <li> <a href ="3.html">WEB</a></li>
    <li> <a href ="4.html">ANDROID</a></li>
  </ol>
<div id = "main">
<br>MAIN : 각 각의 언어를 누르고 세부 프로젝트를 누르면 코드를 볼 수 있습니다.<br>
<p>
  <div id="disqus_thread"></div>
  <script>

  /*
  *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
  *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
  /*
  var disqus_config = function () {
  this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
  this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
  };
  */
  (function() { // DON'T EDIT BELOW THIS LINE
  var d = document, s = d.createElement('script');
  s.src = 'https://king-god.disqus.com/embed.js';
  s.setAttribute('data-timestamp', +new Date());
  (d.head || d.body).appendChild(s);
  })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
</p>
  </div>
  </div>
  </body>
  </html>
