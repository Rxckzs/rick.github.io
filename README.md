# Hello im Rxckzs aka. Rick
## You probably wont know me but it can change.

I will leave some links to my Social Medias or Gameprofiles down there

<p>
  <button onclick="toggleDarkMode()">Toggle Dark Mode</button>
</p>

<p>This is the main content of the page.</p>

<style>
/* Light Theme */
body {
  background-color: #ffffff;
  color: #000000;
}

/* Dark Theme */
body.dark-mode {
  background-color: #121212;
  color: #ffffff;
}

body {
  transition: background-color 0.3s, color 0.3s;
}
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle('dark-mode');
    if (document.body.classList.contains('dark-mode')) {
      localStorage.setItem('theme', 'dark');
    } else {
      localStorage.setItem('theme', 'light');
    }
  }

  window.onload = function() {
    if (localStorage.getItem('theme') === 'dark') {
      document.body.classList.add('dark-mode');
    }
  }
</script>


Socials
======
[Youtube](https://www.youtube.com/@rxckblx)
[Tiktok](https://www.tiktok.com/@.frenter)




Games
------
[Roblox](https://www.roblox.com/users/1922879507/profile)

------


###### Gooodbyee
