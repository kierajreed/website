---
layout: page
---

# Hi! I'm Kiera.

I'm a 20-year-old studying electrical engineering & computer science at MIT.

I like programming, linguistics, urban planning, and robotics.

Welcome! This website is where I keep my writing and project showcases—go <a href="/blog">take a look</a>!

If, for some reason, you're interested in hiring me, I have also posted my <a href="/resume">resume</a>.

<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>
