---
layout: post
title:  "How Javascript is going to ruin my life."
date:   2015-07-16 14:28:43
---

I have a problem. It's permiated my life for a while now. I've learned over the years to keep it under some control. But i always go overboard at first. I can admit this:

<style>
p {
    margin: 40px auto
}

.flash {
    font-size: 40px;
    animation: tada 2s infinite, flash 2s infinite;
}
@keyframes flash {
  0%, 50%, 100% {
    opacity: 1;
    color:yellow;
  }

  25%, 75% {
    opacity: 0;
    color:red;
  }
}
@keyframes tada {
  0% {
    transform: scale3d(1, 1, 1);
  }

  10%, 20% {
    transform: scale3d(.9, .9, .9) rotate3d(0, 0, 1, -3deg);
  }

  30%, 50%, 70%, 90% {
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
  }

  40%, 60%, 80% {
    transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
  }

  100% {
    transform: scale3d(1, 1, 1);
  }
}
</style>




I love <span class="flash">FLASHY</span>.


<p data-height="268" data-theme-id="0" data-slug-hash="yNqyWj" data-default-tab="result" data-user="Pnkdrmmr" class='codepen'>See the Pen <a href='http://codepen.io/Pnkdrmmr/pen/yNqyWj/'>yNqyWj</a> by Austin Matherne (<a href='http://codepen.io/Pnkdrmmr'>@Pnkdrmmr</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>