# Go Static

Promoting the benefits of Static Site Generators and removing the FUD around them


## Story

### What is static?

Static means generating content once (or rather on every change), rather than every time the content is requested.


### What are the benefits of going static?

#### Faster

The speed and efficiency at scale can be up to 8 times faster and therefore 8 times cheaper.
Nothing loads in a browser faster than a plain html file.
Classic webapplications or CMS (like Wordpress, Joomla) generate the html every time they receive a request from a visitor. Once that happens they have to query the database and run through many code to generate the html for the browser. Depending on the used software, hardware and amount of requests this generating needs time which can amount to seconds.
If there is massive increase in traffic and sites overload, this will cause them to slow down or even become unavailable temporarily (called [slashdot effect](https://en.wikipedia.org/wiki/Slashdot_effect)). Most sites use [web caching](https://en.wikipedia.org/wiki/Web_cache) to avoid this.

Exactly therefore Static Site Generators are Web caching inherently.

As a result less server hardware and electricity is needed, so it's a __cheaper__ and __greener__ option compared to a traditional PHP architecture.

<!--
##### Benchmarks
-->

#### Securer

#### file based

Often file based (not all the time however)
  - no database to maintain
  - edit sourcefiles directly and with servertools (grep etc)

#### abstract friendly

Often abstract friendly (not all the time however)


### How is static implemented?

- Caching on Dynamic Sites
- Static Site Generators
- Hybrid Static Site Generators

### Features

Features you expect from common Content-Management-Systems

- Clean URLs and Permalinks 
- HTML-metatags
- RSS are available as extra view 
- third party widgets like maps

#### Replaceable

Theses features can be replaced with clientside JavaScript

- comments (e.g. disqus.com)
- search function, can be substituted external search engines (solr, Google Custom Search)  
- widgets, like current comments, tweets, quotes of the day.

#### Missing

- categories or tags
- webbased content editing
- editorial work-flow

### What implementations already exist?

[Check out the definitive listing at StaticSiteGenerators.net](http://staticsitegenerators.net)



## Contribute

- To update content, [send pull requests on the README.md file](https://github.com/bevry/gostatic/edit/master/README.md)
- To submit designs and to discuss, [use the Issue Tracker](https://github.com/bevry/gostatic/issues)


## License

Public Domain
