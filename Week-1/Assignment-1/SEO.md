#### What is SEO (Search Engine Optimization), and how can web developers optimize their websites for better search engine rankings?

# SEO (Search Engine Optimization) :

Search engines are essential tools in web development, helping users discover relevant information online.
serach engine examples - [google](www.google.com "www.google.com"), [bing](www.bing.com "www.bing.com"), [duckduckgo](www.duckduckgo.com "www.duckduckgo.com"), [yahoo](www.yahoo.com "www.yahoo.com") etc.

# How Search Engine Works :

- Google hase crawler/bot/spider (computer program) which crawles every web site and internal links of web site on internet.
- Crawler gets all information of website like text, images and video etc. and according to that information this website is stored in their corresponding index database.
- when user type query on google then, google use ranking algorithm to fetch data from indexed db.
- Ranking algorith use webstie's data which is stored in indexed database and rank them according to their keyword, website's text, user engagement time.

# How Can Web Developers Optimize their Websites for better Search Engine Rankings :

![SEO for website ranking](./images/Search-engines.png "SEO for website ranking")

1. Site Architecture (11.3%) :

   - Site architecture, also known as SEO architecture, is the foundation of good SEO for your website.
   - architecuter of side should be well arranged, links of pages should be well organised so it will be easy to user and google crawler to crawl your website for indexing.
   - website should not have 3-4 links from home page to desired page.
   - Keeping Things Simple: Especially for larger sites, a simple site architecture makes it easier for users to navigate and find what they need
   - if website is big in size then make html sitemp for user and make xml sitemap for crawler.
   - if you want to checking sitemap working correctly or not, then use google console.

2. Perscribed Domains (19.6%) :

   - google or any other search engine will not give preference to any domain name based on domain names but indirectly it will affect SEO.
   - domain name should be short,unique, it should easyly remembered by user.
   - while using TLD, prefere to use .com beacuse user remember .com easly than other TLD.
   - do not change websites domain name, it will reduce visitor on website, keep same domain for long time.
   - avoid giving - hyphen in domain name.
   - domain name should be contain keyword related to your website content or brand name.
   - use lower case alphabets in url

3. Schema Markup (8.7%) :

   - all main seach engine like google, bing, yahoo etc. decided to make easy process of crawling and indexing, they decided some data or vocabulary should be there on website which is written by website's Creator and reading that data search engine should understand the details of website.
   - Schema Markup is a structured data vocabulary that helps serach engines better understand the information on you website.
   - write details of website in schema, then search engine will read the written information then search engine will understand what is the purpose of website, what is the content in website, what is the type or category of website, what are the services provided by websites.
   - shema data should be structured data so every serach engine will read it properly, now days JSON is used to create schema.
   - it improves appearrence of your website on SERP (Search Engine Result Page).
   - there are many tools online present for creating Schema like ["MARKLE - Schema Generator"](https://technicalseo.com/tools/schema-markup-generator/ "MARKLE")

4. Mobile Friendly (8%) :

   - google search engine gives more priotiy to mobile friendly websites.
   - website can be visit from any type of devices such as, ipad, computer,mobiles etc. because of this reason website should be responsive.
   - when google search engine test our website using mobile bot wheather website is mobile friendly or not, according to that also our web site gets ranking.
   - we can check our website is mobile friendly or not using google console and if there are some errors then it will show.

5. Social Media (5.3%) :

   - search engines can't ignore the imporatance of social media, social signals were implemented in the serach engine algorithms, which affect ranking.
   - the more popular the website is on social media, the more significance will hold in the search engines results. that's why companies so actively using social media and it's power can not be ignored.
   - Sharing links to your website on your social media profiles can drive more traffic to your site. More traffic can lead to higher rankings on search engines.

   - !["Social Media SEO"](./images/social%20media%20seo.png "Social Media SEO")

6. Tags (3%) :

   - `<H1>` tag should be used for only one time in all page for main heading,
     then for other content you can use `<h2>` to `<h6>` tags.
   - `<title>` tag stores title of website, add main keyword or brand name in title, do not use same keyword more than 1 in title, give different title to every page but brand name or main keyword must be there in every page title.
   - `<meta name="description" content="description details" >` - description meta tags and `<title>` tag information shown in search engine result page, if we give attractive title and description then there is chances user can click on website.
   - `<meta name="keyword" content="keyword list" >` - keyword mata tag used to write keywords for search engine.
   - `<meta name="robots" content="index, follow" >` - robots meta tag used for giving permission to crawler for crawling our website's internal links and allowing for indexing our website.
   - `<link rel="canonical" href="https://www.website.com">` - cononical tag is used when user enters many combination of our website like - https://www.website.com or http://www.website.com or http://website.com etc. then which main website should be shown to user that we write in canonical tag, what ever url you will give in canonical tag that url will be considered by crawler for indexing.
   - if you have 2 more webpages with same content but differenct url like https://wwww.website.com/contact , https://wwww.website.com/address, https://wwww.website.com/aboutus then in this case crawler will be confussed which one is main webpage for indexing then we provide <link rel="canonial" href="https://wwww.website.com/contact"> this cononical tag to crawler for understanding which webpage is main webpage.
   - Canonical tags only used on **internal-webpages** or **_non-main_** webpages.
   - `<Strong>`, `<em>`, `<main>`, `<header>`, `<footer>` `<aside>` etc. symentic tags also important for SEO.
   - for checking `<title>` and `<meta name="description" content="description in details">` has been written correctly or not use this website - ["totheweb"](https://totheweb.com/learning_center/tool-test-google-title-meta-description-lengths/ "totheweb.com")

7. Loading Speed (5%) :

   - for increasing loading speed of website, we have to minify js and html, css files and css,html and js file should be loaded asychronously.
   - Defer large size of js files because without loadning html, css user can not use any event of javascript on website.
   - choose right hoisting option for your website.
   - use media compression for images, according to google image size should be 100kb, convert images in next generation format eg. webp (webp 10kb image quality is equal to the jpeg 100kb image).
   - Enable browsing chache.
   - Apply content delivery network (CDN) eg. if your hosting your web site in india and request is comming from united states then in this case it will take time to respose, so better use CDN because CDN is globally available, CDN root is available in united state.
   - if you attach css in HTML only then it will take time to load, instead of adding css directly in HTML file, provide external link of css same with js.
   - Enable lazy load.
   - Regular Monitoring of Website speed.
   - use following tools for checking website's speed - ["Page Speed Website"](https://pagespeed.web.dev/ "Page Speed Website") or ["GT Matrix"](https://gtmetrix.com/ "GT Matrix")

8. Content (13.1%) :

   - SEO content writing is the process for both website's user and Search engine.
   - the primary goal is to plan, create an optimize content for google and other search engine for better ranking.
   - Elements of SEO content
     - Keyword Research and optimization
     - Convert Keywords into topics
     - internal and external linking (add links of other websites or our internal links this is good for SEO)
   - if you have put reference link in content then use `<a>hyperlink's word should be related with opening website's content</a>` tag.
   - use keyword naturally and with in limit inside content, don't forcefully use or over use of keyword everywhere in content it will create negative impact in SEO
   - use images with alt attribute `<img src="image path" alt="intention of image">`.
   - write indepth or comprehensive content, so user will get every details information on your website otherwise user will visit other website for information and then you will lose chances of comming back to your content.
   - Avoid Plagiarism for better SEO, write unique / original content, Avoid article spinning, use tool - ["smallseotools - plagarism Checker tool"](https://smallseotools.com/plagiarism-checker/ "smallseotools - plagarism Checker tool").
   - avoid spelling and grammer mistake in content, use tools for checking web site's grammer and spelling - ["spell check"](https://www.online-spellcheck.com/ "spell check") and ["Grammer check"](https://www.grammar.com/ "Grammer check").

9. Keywords (13%) :

   - Keyword is word or pharase that describe your content on webpage
   - basesd on used keyword in webpage content, search engine can rank our website.
   - short tail means general query (eg. shoes, laptop, bottle etc.) and long tail query means more specific query (eg. best running shoes for women, 32 gb RAM Dell Laptop, platic white bottle of altasware brand).
   - on short tail keyword compition is very high and on long tail keyword compition is less compare to short tail keyword.
   - Keywords can be used in meta tag, content of our web page.
   - so many online tool available, by using that tools we can search rankable keyword related to our website content.

10. Backlinks (13%) :

    - Backlinks are links from outside domains that point to pages on your domain.
    - backlinks are important for SEO because they represent trust form one website to another website.
    - but google sugest to create limited backlinks, otherwise website will be added to blacklist or website will be considered as spam.
    - backlink should be written in `<a>` tag and hyperlink text word should be related to opening website's content.
