---
layout: default
title: "HTML5 Development version of Card Pirates"
---

<p class='lead'>This is the latest <strong>development</strong> version of Card Pirates. It's extremely rough, as we've only been working on it a few days! You can currently click on cards to move around. It's only likely to work in modern browsers.</p>

<p class='lead'>Please let us know what you think in the <a href='#comments'>comments</a> underneath the game.</p>

<canvas id="GameCanvas" width='1024' height='768' tabindex='1'></canvas>
<textarea id="GameConsole" style="display:none" readonly></textarea><br>
<script language="javascript" src="main.js">Javascript not supported!</script>

<h2 name='comments'>Comments</h2>

<div id="disqus_thread" style='margin-right: 200px'></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    var disqus_shortname = 'cardpirates'; // required: replace example with your forum shortname
    var disqus_url = '{{ site.url }}';

    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>

<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
<a href="http://disqus.com" class="dsq-brlink">comments powered by <span class="logo-disqus">Disqus</span></a>
