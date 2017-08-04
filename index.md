---
layout: default
title: Getting Started
quote: The essential part of creativity is not being afraid to fail.
cite: Edwin H. Land
---

This example is just meant to get you started and show you a little of what's
possible with GitHub Pages. In just 3 simple steps, you will have your own
website.

1. [Create a Github account](https://github.com/join)
2. [Fork this repository](https://github.com/chesshacker/pages-starter/fork)
3. Edit the `_config.yml` file

{% highlight yaml %}
title: {{ site.title }}
description: >
  {{ site.description | rstrip }}
baseurl: "{{ site.baseurl }}" # the subpath of your site
url: "{{ site.url }}"
email: {{ site.email }}
github_username:  {{ site.github_username }}
linkedin_username: {{ site.linkedin_username }}
twitter_username: {{ site.twitter_username }}
{% endhighlight %}

That's it! You should now have a website of your own. Well if you played attention at least.

To see if you did it right type this link in https://`your github username`.github.io/pages-starter/ if you didn't well then keep on tyring, lets hope you get it done before class is over.

There's so much more you can do with GitHub Pages, so don't stop here, unless you want to give up.
Explore the code in this project and start making it your own, if you like doing this.
Continue on to the [Resources]({{ "/resources" | prepend: site.baseurl }})
section to learn more about GitHub Pages and other handy tools, it'll help you if you care.

If you have questions, please let me know. I am glad to help! In other words, don't be shy to "embarrass" yourslef with questions. Ask away.
