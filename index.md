---
title: A simple starter kit for Eleventy
heading: Testing 12345
---
Hoooooooooylia is a lightweight [Eleventy](https://11ty.io) starter kit with [Netlify CMS](https://www.netlifycms.org/) pre-configured, so that you can one-click install a progressive, accessible blog in minutes. It also gives you a well organised starting point to extend yourself. It’s by [Andy Bell](https://twitter.com/hankchizljaw) and [friends](https://github.com/aarongustafson/hylia/graphs/contributors).

Get started now by [deploying Hylia to Netlify.](https://app.netlify.com/start/deploy?repository=https://github.com/hankchizljaw/hylia&stack=cms)

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