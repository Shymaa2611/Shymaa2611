### Hi there 👋

<pre>
```html
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;style&gt;
  p {
    color: red;
    font-size: 45px;
    width: 1000px;
    margin: 30px auto;
    border-right: 2px solid var(--main-color);
    overflow: hidden;
    white-space: nowrap;
    animation: control-width 3s steps(28) infinite, blink 0.5s infinite;
  }
  
  @keyframes control-width {
    from {
      width: 0;
    }
    to {
      width: 1000px;
    }
  }
  
  @keyframes blink {
    from {
      border-right-color: var(--main-color);
    }
    to {
      border-right-color: transparent;
    }
  }
&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;

&lt;p id="animatedText"&gt;Hello Friends 😊&lt;/p&gt;

&lt;script&gt;
  var animatedText = document.getElementById("animatedText");

  function animateText() {
    setTimeout(function() {
      animatedText.innerHTML = "&lt;p&gt;I am a backend developer&lt;/p&gt;";
      setTimeout(function() {
        animatedText.innerHTML = "&lt;p&gt;I'm interested in [ &lt;span style='color: blue;'&gt;Django Framework - FastAPI &lt;/span&gt; ]&lt;/p&gt;";
        animateText(); 
      }, 3000); 
    }, 3000); 
  }

  animateText(); 
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;
```
</pre>


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
