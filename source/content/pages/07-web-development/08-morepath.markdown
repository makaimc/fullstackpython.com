title: Morepath
category: page
slug: morepath
sortorder: 0708
toc: False
sidebartitle: Morepath
meta: Morepath is a Python web framework with a model-driven design approach. Learn more about Morepath on Full Stack Python. 


# Morepath
[Morepath](http://morepath.readthedocs.org/en/latest/) is a micro web 
framework with a model-driven approach to creating web applications and web
APIs.

Morepath's framework philosophy is that the data models should drive the
creation via the web framework. By default, the framework routes URLs directly 
to model code, unlike for example Django which requires explicit URL routing
by the developer.


## Why is Morepath an interesting web framework?
Simple [CRUD web applications and APIs](http://en.wikipedia.org/wiki/Create,_read,_update_and_delete) 
can be tedious to build when they are driven straight from data models without
much logic between the model and the view. Learn more about how Morepath
[compares with other web frameworks](http://morepath.readthedocs.org/en/latest/compared.html)
from the creator.

With the rise of front end JavaScript frameworks, many Python web frameworks 
are first being used to build 
[RESTful APIs](/application-programming-interfaces.html) that return JSON
instead of rendering HTML via a templating system. Morepath appears to have 
been created with the RESTful API model approach in mind and cuts out the 
assumption that templates will drive the user interface.

<div class="well see-also">Morepath is an implementation of the <a href="/web-frameworks.html">web frameworks</a> concept. Learn how these parts fit together in the <a href="/web-development.html">web development</a> chapter or view <a href="/table-of-contents.html">all topics</a>.</div>


### Morepath resources
Morepath, with 
[its first commit using the Morepath name in 2013](https://github.com/morepath/morepath/commit/9c4f772dc48658a63ae2b46f6c1863220608f15e), 
is a much newer web framework than Django, Flask or Pyramid, which results
in fewer tutorials. There is also a lot of opportunities for newer Python 
developers to fill the gaps with their own Morepath tutorials. However, 
these resources below are a good place to get started. 

* [On the Morepath](http://blog.startifact.com/posts/on-the-morepath.html)
  is a blog post by Startifact on how they use Morepath and some of the
  features of the framework.

* [A Summer with Morepath](http://blog.stacktrace.ch/post/132538261985)
  describes the author's experience using Morepath, such as how he built
  a framework around Morepath's core functionality. He eventually became
  a core contributor to Morepath based on the application he created.

* [Build a better batching UI with Morepath and Jinja2](http://blog.startifact.com/posts/morepath-batching-example.html)
  is an introductory post on building a simple web application with the 
  framework. The code for the application is also 
  [open source and available on GitHub](https://github.com/morepath/morepath_batching).

* [podcast.\_\_init\_\_ interviewed Martijn Faassen](https://www.podcastinit.com/episode-91-morepath-with-martijn-faassen/)
  about Morepath and he described what makes the framework different from
  other existing web frameworks as well as why someone should be convinced
  to switch for a new project.

* Morepath's creator gave a 
  [great talk on the motivation and structure for the new framework](https://www.youtube.com/watch?v=gyDKMAWPyuY) 
  at EuroPython 2014.

