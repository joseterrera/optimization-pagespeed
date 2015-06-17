This is project 4 for Udacity's Front-End NanoDegree. It was for me an introduction to timelines and website optimization. I think it has opened my head as to how to deliver a website now, and the importance of efficiency: one may have a great design, or great content, but it is kind of a downer if the site moves slowly.

On project 4, part 1, I used pagespeed to improve the portfolio's performance.
To do this I used ngrok which exposes my localhost to the web traffic. I found especially helpful this site to make it work together with pagespeed:
http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/

Pagespeed is relatively easy to use. Just use any site, and follow their directions to speed up things. There's a lot of documentation about it.


I also used grunt that does the job when it comes to minfiying, compiling, and all those things that you normally have to do when building a site. If you are new to this, here is a good link:
http://code.tutsplus.com/tutorials/meet-grunt-the-build-tool-for-javascript--net-24856

On project 4, part 2, I had to fix a crazy pizza site that builds pizzas, changes their sizes, and has constantly pizzas moving on the background. There were many things in the js file that were slowing things down a lot, and complicating them unnecessarily.

I've improved several functions that were slowing down the page significantly. In some of them, it was a matter of re-arranging functions, breaking down variables, or better selecting the elements in the dom, or applying more efficient css methods (i.e style.left vs. translate). I kept testing the fps with chrome's timeline, until it was at least 60 fps.
Additionally, I also modified the css, so that it is no longer render blocking.
