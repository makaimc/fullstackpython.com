title: DevOps
category: page
slug: devops
sortorder: 1101
toc: True
sidebartitle: 11. DevOps
meta: DevOps combines software development and application operations. Python is often used in the DevOps toolchain.


# DevOps
DevOps is the combination of application development and operations, which
minimizes or eliminates the disconnect between software developers who build 
applications and systems administrators who keep infrastructure running.


## Why is DevOps important?
When the Agile methodology is properly used to develop software, a new
bottleneck often appears during the frequent [deployment](/deployment.html) 
and operations phases. New updates and fixes are produced so fast in each 
sprint that infrastructure teams can be overwhelmed with deployments and 
push back on the pace of delivery. To allievate some of these issues, 
application developers are asked to work closely with operations folks to
automate the delivery from development to production. 

## DevOps tooling resources
* [DevOps: Python tools to get started](https://speakerdeck.com/victorneo/devops-python-tools-to-get-started)
  is a presentation slideshow that explains that while DevOps is a culture, 
  it can be supported by tools such as Fabric, Jenkins, BuildBot and Git
  which when used properly can enable continuous software delivery.

* [A look at DevOps tools landscape](https://devup.co/a-look-at-devops-tools-landscape-7220099c6b81)
  provides an introductory overview of the tooling that is typically
  required to perform DevOps. The tools range from source control systems,
  continuous integration, containers to orchestration. For an 
  Atlassian-centric perspective on tooling, take a look at this post on
  [how to choose the right DevOps tools](http://blogs.atlassian.com/2016/03/how-to-choose-devops-tools/)
  which is biased towards their tools but still has some good insight
  such as using automated testing to provide immediate awareness of 
  defects that require fixing.


## General DevOps resources
* [DevOps vs. Platform Engineering](https://alexgaynor.net/2015/mar/06/devops-vs-platform-engineering/)
  considers DevOps an ad hoc approach to developing software while building
  a platform is a strict contract. I see this as "DevOps is a process", 
  while a "platform is code". Running code is better than any organizational 
  process.

* [So, you've been paged](http://blog.scalyr.com/2016/09/so-youve-been-paged/)
  provides their development team's "Communicate -> Learn -> Act" structure
  for handling production issues based on lessons learned from their years 
  of experience dealing with incidents.

* [Operations for software developers for beginners](https://jvns.ca/blog/2016/10/15/operations-for-software-developers-for-beginners/)
  gives advice to developers who have never done operations work and
  been on call for outages before in their career. The advantage of DevOps
  is greater ownership for developers who built the applications running
  in production. The disadvantage of course is the greater ownership
  also leads to much greater responsibility when something breaks!

* [Why are we racing to DevOps?](http://www.cio.com/article/3015237/application-development/why-are-we-racing-to-devops.html)
  is a very high level summary of the benefits of DevOps to IT organizations.
  It's not specific to Python and doesn't dive into the details, but it's 
  a decent start for figuring out why IT organizations consider DevOps the
  hot new topic after adopting an Agile development methodology.

