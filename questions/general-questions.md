# General Questions:

* What did you learn yesterday/this week?
> I learned how to properly use the flexbox layout in CSS. The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities. Source: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox
* What excites or interests you about coding?
> The thing that excites me the is to be able to build something new from scratch just by using my brain and a computer. The possibilities of what you are able to create are infinite.
* What is a recent technical challenge you experienced and how did you solve it?
> I had to retrieve data from Microsoft's Active Directory by using LDAP. It was a first for me and I found the filters syntax to be a bit confusing in the beginning. But after checking several examples over the Internet I was able to make it work.
* When building a new website or maintaining one, can you explain some techniques you have used to increase performance?
> 1. Image Optimization by applying lossless and/or lossy compression techniques and only using images with the right size.
> 2. HTTP Requests Number Reduction. When your browser fetches data from a server it does so using HTTP (Hypertext Transfer Protocol). It is a request/response between a client and a host. In general, the more HTTP requests your web page makes the slower it will load. There are many ways you can reduce the number of requests such as:

> * Inline your Javascript (only if it is very small)
> * Using CSS Sprites
> * Reducing assets such as 3rd party plugins that make a large number of external requests
> * Don’t use 3rd party frameworks unless they are absolutely needed
> * Use less code!
> * Combining your CSS and JS files (with HTTP/2 concatenation is no longer as important)

> 3. CSS and Javascript Minification.
> Minification of resources means removing unnecessary characters from your HTML, Javascript, and CSS that are not required to load, such as:

> * Whitespace characters
> * New line characters
> * Comments
> * Block delimiters

> This speeds up your load times as it reduces the amount of code that has to be requested from the server.
> Source: https://www.keycdn.com/blog/website-performance-optimization
* Can you describe some SEO best practices or techniques you have used lately?
* Can you explain any common techniques or recent issues solved in regards to front-end security?
> HTTPS used on every page and for all external content (plugins, images...).
> X-Frame-Options
The X-Frame-Options header (RFC), or XFO header, protects your visitors against clickjacking attacks. An attacker can load up an iframe on their site and set your site as the source, it's quite easy: <iframe src="https://scotthelme.co.uk"></iframe>. Using some crafty CSS they can hide your site in the background and create some genuine looking overlays. When your visitors click on what they think is a harmless link, they're actually clicking on links on your website in the background. That might not seem so bad until we realize that the browser will execute those requests in the context of the user, which could include them being logged in and authenticated to your site!
> Source: https://github.com/thedaviddias/Front-End-Checklist#security
* What actions have you personally taken on recent projects to increase maintainability of your code?
* Talk about your preferred development environment.
> Depending on the technology I'm using my development environment varies a bit. If I'm working with HTML, CSS and a Javascript framework or library I love using Visual Studio Code and npm. If I'm working with ASP.NET MVC Core then I normally use Visual Studio 2017 also combined with npm and entity framework core.
* Which version control systems are you familiar with?
> In the past I've used Team Foundation Server for some projects. Lately, I mostly use git.
* Can you describe your workflow when you create a web page?
* If you have 5 different stylesheets, how would you best integrate them into the site?
* Can you describe the difference between progressive enhancement and graceful degradation?
* How would you optimize a website's assets/resources?
* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
* Name 3 ways to decrease page load (perceived or actual load time).
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* Describe how you would create a simple slideshow page.
* If you could master one technology this year, what would it be?
* Explain the importance of standards and standards bodies.
* What is Flash of Unstyled Content? How do you avoid FOUC?
> A flash of unstyled content (FOUC, also flash of unstyled text or FOUT)[1][2] is an instance where a web page appears briefly with the browser's default styles prior to loading an external CSS stylesheet, due to the web browser engine rendering the page before all information is retrieved. The page corrects itself as soon as the style rules are loaded and applied; however, the shift may be distracting. Related problems include flash of invisible text (FOIT) and flash of faux text
> Source: https://en.wikipedia.org/wiki/Flash_of_unstyled_content

> The way to prevent it is this: "Put all your styles in <head> and make sure that any script that asks for layout information comes after them"
> Source: https://bugzilla.mozilla.org/show_bug.cgi?id=1404468

* Explain what ARIA and screenreaders are, and how to make a website accessible.
> Accessible Rich Internet Applications (ARIA)  is a set of attributes that define ways to make Web content and Web applications (especially those developed with Ajax, JavaScript and more recent web technologies like Bootstrap) more accessible to people with disabilities. For example, ARIA enables accessible navigation landmarks, JavaScript widgets, form hints and error messages, live content updates, and more.
> ARIA is a set of special accessibility attributes which can be added to any markup but is especially suited to HTML. The role attribute defines a specific role for type of object (such as an article, alert, slider or a button). Additional ARIA attributes provide other useful properties, such as a description for a form or the current width of a progress bar. ARIA attributes can also be used to specify active or disabled state for objects (especially buttons).
> Source: https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
* What does CORS stand for and what issue does it address?
> Cross-Origin Resource Sharing (CORS) is a mechanism that uses additional HTTP headers to tell a browser to let a web application running at one origin (domain) have permission to access selected resources from a server at a different origin. A web application makes a cross-origin HTTP request when it requests a resource that has a different origin (domain, protocol, and port) than its own origin.

> An example of a cross-origin request: The frontend JavaScript code for a web application served from http://domain-a.com uses XMLHttpRequest to make a request for http://api.domain-b.com/data.json.

> Source: https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
