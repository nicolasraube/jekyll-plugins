Jekyll Plugin: Sitemap.xml Generator
====================================

Sitemap.xml Generator is a Jekyll plugin that generates a sitemap.xml file by traversing all of the available posts and pages. This fork is specifically modified to fit the needs for my personal website, www.nicolasraube.com .

Author: Michael Levin ([http://www.kinnetica.com](http://www.kinnetica.com))
Configuration Update: Daniel Groves ([http://danielgroves.net](http://danielgroves.net))

This work, "nicolasraube/jekyll-sitemap-generator", is a derivative of "kinnetica/jekyll-plugins" by Michael Levin, used under CC BY. "nicolasraube/jekyll-sitemap-generator" is licensed under CC BY 3.0 by Nicolas Raube.

Changes I, Nicolas Raube, made:
- exclude certain files from being added to the sitemap
- adds portfolio collection entries to sitemap
- only adds lastmodified property if the page is a blog post and then only uses front matter 'date' value
- auto add priority value to blog posts and portfolio collection entries

Distributed Under A [Creative Commons](http://creativecommons.org/licenses/by/3.0/) License
