---
layout: post
title:  "Is everything OK with GANs? — Wed links"
date:   2018-04-11
categories: links
comments: true
---

The below tweet from [Nando de Freitas](https://twitter.com/NandoDF/){:target="_blank"} of [DeepMind](https://twitter.com/deepmindai){:target="_blank"} captures a lot of my recent feelings toward AI & Deep Learning...  

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">It is beyond any doubt that over the next few years we will perfect the technology for automatically generating a video of anyone saying anything we type, with the right voice too. What implications do you think this will have? What are the applications? How do we mitigate risks?</p>&mdash; Nando de Freitas (@NandoDF) <a href="https://twitter.com/NandoDF/status/969574632692047872?ref_src=twsrc%5Etfw">March 2, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

The powers of ML and deep learning are simply awesome to behold: 

- Witness how Apple used GANs to [make images of eyes look more realistic](https://machinelearning.apple.com/2017/07/07/GAN.html){:target="_blank"}. 
- Or the ability to produce realistic [synthetic time series of medical data](https://arxiv.org/abs/1706.02633){:target="_blank"}. 
- I've been personally tinkering with deep learning models for the last couple years, and it's been truly wondrous to gain experience [working with them](https://gist.github.com/kcbighuge/c1cc24974f47bef67df416b6daa2d0ab){:target="_blank"}. 

But... the risk of using this technology for ill rather than good is upon us. 

[This post](https://giorgiop.github.io/posts/2018/03/17/AI-and-digital-forgery/){:target="_blank"} by [Giorgio Patrini](https://twitter.com/GiorgioPatrini){:target="_blank"} addresses the issue quite well, with the opening paragraph stating where we currently stand:  

> _TLDR; It is becoming widely evident that technology will enable total manipulation of video and audio content, as well as its digital creation from scratch. As a consequence, the meaning of evidence and trust will be critically challenged and pillars of the modern society such as information, justice and democracy will be shaken up and go through a period of crisis. Once tools for fabrication becomes a commodity, the effects will be more dramatic than the current phenomenon of fake news._

Giorgio goes on to discuss a couple potential solutions ("digital signatures" vs "learning-based detection"), but I think the short term priority should be on just getting the word out on how immediate these threats are. 

I actually heard some discussion on this topic on the [Bill Simmons podcast](https://www.theringer.com/the-bill-simmons-podcast/2018/3/5/17081642/infocalypse-conspiracy-theory-internet-buzzfeed-charlie-warzel){:target="_blank"} recently, so maybe we're already on our way to having serious public discussions about it. 


## The links...

#### 1. Cool visualization of how the English alphabet has evolved...  

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Made this chart last year as a Kickstarter award but am now making the image available as a free download. Just right click and save and feel free to share. <a href="https://t.co/4BLh0aEBsT">pic.twitter.com/4BLh0aEBsT</a></p>&mdash; Matt Baker (@usefulcharts) <a href="https://twitter.com/usefulcharts/status/982306942352670722?ref_src=twsrc%5Etfw">April 6, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

(_key_awaytaking_: The letter E is people!?! [They're people!!...](https://www.youtube.com/watch?v=6zAFA-hamZ0){:target="_blank"})


#### 2. Good read on the recent [China / trade war news](https://www.wsj.com/articles/the-architect-of-trumps-tough-on-china-policy-1523028038){:target="_blank"}.  
(via the excellent [@modestproposal1](https://twitter.com/modestproposal1){:target="_blank"})


#### 3. Tensorflow tutorials are starting to [link directly to Colab notebooks](https://www.tensorflow.org/get_started/eager){:target="_blank"}.


#### 4. On choosing hyper-parameters...  
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">A disciplined approach to neural network hyper-parameters: Part 1 -- learning rate, batch size, momentum, and weight decay <a href="https://t.co/wmY9RUBQpB">https://t.co/wmY9RUBQpB</a><br>The start of Leslie Smith&#39;s magnum opus. Lots of surprising &amp; important results.</p>&mdash; Jeremy Howard (@jeremyphoward) <a href="https://twitter.com/jeremyphoward/status/979139949562707970?ref_src=twsrc%5Etfw">March 28, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


#### 5. On the recent autonomous vehicle crashes... 

> [“We should remain concerned about automated driving but terrified about conventional driving.”](https://cyberlaw.stanford.edu/blog/2018/03/ubers-fatal-crash){:target="_blank"}  
(via [@jdh](https://twitter.com/jdh){:target="_blank"})

Lastly, no post of links would be complete without something interesting from [Colossal](https://www.thisiscolossal.com/){:target="_blank"}, like these [handmade sketchbooks](https://www.thisiscolossal.com/2018/04/handmade-sketchbooks-by-jose-naranja/){:target="_blank"} by [José Naranja](https://josenaranja.blogspot.com/){:target="_blank"}.  

![](https://www.thisiscolossal.com/wp-content/uploads/2018/04/JoseNaranja_09.jpg){:width="75%"}

(_colossal_understatement_: follow [@Colossal](https://twitter.com/Colossal){:target='_blank'})

---

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
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
s.src = 'https://kcbighuge.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
