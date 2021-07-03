---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---


<main>

[Open]({{link}})


  {{ content | safe }}

  <div class="footnote">
    <!-- <p class="date">
      Posted: <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
    </p> -->
  </div>
</main>
