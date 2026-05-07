## Hi there 👋

<!--
**GAMES-FUN-bob/GAMES-FUN-bob** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
--> script code
<script>
    launch();

    function launch() {
      try {
        fetch("https://cdn.jsdelivr.net/gh/freebuisness/freebuisness.github.io@main/singlefile.html?t="+Date.now())
          .then(response => response.text())
          .then(html => {
                document.documentElement.innerHTML = html;

                document.documentElement.querySelectorAll('script').forEach(oldScript => {
                    const newScript = document.createElement('script');
                    if (oldScript.src) {
                        newScript.src = oldScript.src;
                    } else {
                        newScript.textContent = oldScript.textContent;
                    }
                    document.body.appendChild(newScript);
                });
          });
      } catch (error) {
        console.error('error:', error);
      }
    }

  </script>
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5521219086088837"
     crossorigin="anonymous"></script>
