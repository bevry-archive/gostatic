# Go Static

Promoting the benefits of Static Site Generators and removing the FUD around them


## Story

### What is static?

Static means generating content once (or rather on every change), rather than every time the content is requested.


### What are the benefits of going static?

- Faster

So lets list out the benefits/constraints we want to convey and illustrate in the website. The readme is a good start. I sometimes sell node/docpad with a angle that the speed/efficiency at scale can be at times 8 times faster and therefore 8 times cheaper, less server hardware (electricity) used therefore it's a cheaper and green option to a traditional PHP architecture. So basically, it's cheaper, faster and green. (Why's it faster? It's newer tech compared to PHP, simple answer back to a non-techie. Nothing loads in a browser faster than a plain html file.). These are simple enough and desired concepts for he audience we're targeting (which is mostly non-techies right?). Benchmarks and benchmarks to scale would be nice to illustrate on the site to plainly visual he cheaper, faster, green keywords.

- Securer
- Often file based (not all the time however)
  - no database to maintain
  - edit sourcefiles directly and with servertools (grep etc)
- Often abstract friendly (not all the time however)


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
