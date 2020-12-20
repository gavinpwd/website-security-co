# website-secuirty-co
### by Gavin Pili

### **TL;DR**  a simple looking website that communicates the main features and benefits of the business.  A minimalist colour palette with a burst of bright tones that evokes an elegant yet inviting website.
**You can view the webpage here: https://gavinpwd.github.io/website-secuirty-co/**

This webpage was created using the following:

* HTML5, CSS3, Bootstrap 5
* Google Fonts API
* Font Awesome Icons v4.7.0 library

**The Brief**
* Your mission is to build a simple looking website that communicates the main features and benefits of the business.

**Key considerations and requirements**

* Create a simple looking website that is SECURE
* Needs to be super fast
* Mobile responsive or mobile first (over static) is preferred
* Needs to be easy to manage and open to add-ons
* Lead magnet (look up to outgrow.co for inspo)
* It can be a staged approach (not expecting a finsihed product)
* Communicate the features and benefits clearly
* Call to action. What you’d include if it were YOUR business


**My Response to the Brief including some research notes**
1. Simple looking
- Use of a minimal colour palette, use of svg graphics, no stock images
- Website has three sections — carousel menu that shows (1) what the business is about, statistics and reasons why; (2) Benefits section outlines the four main benefits of the product (service); (3) Features section outlines the four main features of the product (service).  All three have links.

2. Secure
- Currently securely hosted at github for a demo
- An SSL certificate needs to be purchased and installed to secure the website if deployed on another hosting site. Secure web servers running Apache or IIS are good starting points.
- Use Coding Best Practices: The OWASP Top 10 is a standard awareness document for developers and web application security.  Using the OWASP Top 10 is perhaps the most effective first step towards changing the software development culture within your organization into one that produces more secure code. (https://owasp.org/www-project-top-ten/) 
- Use Cybersecurity Best Practices: CIS Controls and CIS Benchmarks are global industry best practices.  CIS Controls to quickly establish the protections providing the highest payoff in their organizations. CIS Benchmarks are proven guidelines will enable you to safeguard operating systems, software and networks that are most vulnerable to cyber attacks. (https://www.cisecurity.org/cybersecurity-best-practices/)

3. Super fast
- This webpage uses Bootstrap with little javascript built-in. 
- The benefit of using Bootstrap CDN is its ability to deliver content quickly and efficiently.
- Website has responsive design which is Google’s preferred design pattern. (https://developers.google.com/search/mobile-sites/mobile-seo/responsive-design)
- Follow best practices for coding semantics, image specs, minifying code, using svg sprite.
- Consider using lazy loading to improve page loading speed when using videos or images on the website (https://web.dev/lazy-loading/)
- Analyse and optimise website with PageSpeed tools — PageSpeed Insight lets you obtain your PageSpeed score and use PageSpeed suggestions to make your web site faster through our online tool; PageSpeed Modules run on Apache or Nginx server to automatically rewrite and optimize resources on your web site. (https://developers.google.com/speed)

4. Mobile responsive
- Bootstrap allows you to quickly design and customize responsive mobile-first sites.
- I used media queries to render the website on mobile, tablet and desktop browsers.  I used Chrome Dev Tools to test the website.

5. Easy to manage and open to add-ons
- I chose Bootstrap over W3.CSS because it is more popular (20M websites), has more programmers, templates, plug-ins and snippets available versus W3.CSS (70K websites) (https://blog.hubspot.com/website/w3-css-vs-bootstrap/)
- Easy management: Consider building a CI/CD Pipeline in the cloud — a continuous integration/continuous deployment pipeline.  An example would be using GitHub for version control, Code Anywhere for dev environment, Travis CI for CI service, Code Climate for testing, and Heroku for production environment. (https://www.leadingagile.com/2018/06/build-a-ci-cd-pipeline-in-the-cloud-part-one/)  This framework helps DevOps teams ship higher quality software, faster, for improved software deployment. (https://about.gitlab.com/blog/2019/06/27/positive-outcomes-ci-cd/)

6. Lead magnet
- Implemented call-to-action buttons that are fun (Take a Quiz), informative (Why is Patching Challenging?) and invitation to connect (Let’s Talk Solutions) without sounding too needy.
- Consider adding Google Analytics on the html document to track user activities.
- Consider adding a video landing page that is CDN hosted like Vidyard to drive customer engagement without slowing down the website.  Use video analytics to learn more about your audience. (https://www.vidyard.com/)
- Adding interactive content to drive customer interaction on the website and generate leads for example -- podcasts, blogs, quizzes, chatbots, prizes or calculators. An example is Ion (https://en.rockcontent.com/platform/interactive-content-solutions/) which is a competitor of outgrow.co
- Create great content and copywriting using keywords that are SEO optimised

7. A staged approach
- Refer to point 4(i)
- Consider adopting Agile phoilosophy and Scrum methodology because both focuses on delivering software early and often, are iterative processes, and accommodate change. They also encourage transparency and continuous improvement. (https://hbr.org/2016/05/embracing-agile)


**What needs to be done:**
* Minify code
* Write correct SVG Sprite and use on the document
* Add contents as per navigation links
* Add optimised images
* Add Video landing page via CDN
* Add Google Analytics on markup


**Here is a sample screenshots of the webpage:**
Desktop View

![Desktop View](/images/desktop-view.png)




Tablet View

![Tablet View](/images/tablet-landscape.png)




Mobile View

![Mobile View](/images/mobile-view.png)




Desktop Lighthouse Results using Chrome Dev Tools

![Desktop Lighthouse](/images/desktop-lighthouse.png)




Mobile Lighthouse Results using Chrome Dev Tools

![Mobile Lighthouse](/images/mobile-lighthouse.png)





Style Guide inspired by the image from the brief

![Style Guide](/images/style-guide.png)
