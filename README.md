### Hi there 👋

<!DOCTYPE html>
<html>
<head>
<style>
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
</style>
</head>
<body>

<p id="animatedText">Hello Friends 😊</p>

<script>
  var animatedText = document.getElementById("animatedText");

  function animateText() {
    setTimeout(function() {
      animatedText.innerHTML = "<p>I am a backend developer</p>";
      setTimeout(function() {
        animatedText.innerHTML = "<p>I'm interested in [ <span style='color: blue;'>Django Framework - FastAPI </span> ]</p>";
        animateText(); 
      
      }, 3000); 
    }, 3000); 
  }

  animateText(); 
</script>

</body>
</html>




- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
