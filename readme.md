
## Original Site

- created by [Strategem Group Marketing](https://linkedin.com/company/strategem-group) in St. Charles, IL
- powered by Joomla 1.5 ([reached end of life in 2012](https://docs.joomla.org/Joomla_1.5_version_history))
- timestamps indicate it is rarely updated

## Quick teardown

- What do you use Joomla for primarily? Blog posts? Search?
- What are your conversion goals and how are you tracking them?
- Analytics provider?
- What is the main story you are trying to tell?
- logo, Facebook link, phone number, address, 38 years in the business!
- 19 static pages: home, about us, our staff, our companies, customer service, client spotlight, free gift, services, personal insurance, commercial insurance, other insurance, emergency claim reporting, auto quote landing, life quote landing, home quote landing, business quote landing, helpful links/resources, FAQs, contact us
- 8 PDF links: life quote, auto quote, home quote, commercial quote, auto loss notice, property loss notice, first report of injury (workers compensation), teen and parent driving contract
- 3 forms: newsletter signup, renewal questionnaire, literature request
- 2 external links: american collectors, progressive pet insurance
- 13 articles (blog posts)
- 9 testimonials (could each be blog posts)
- 9 Gordie’s giggles (could also be blog posts)
- 2 pages that could be blog posts: client spotlight,
- in total, 31 potential blog posts + 19 static pages = 50 pages
- 1 potentially expired page: help us celebrate 35 years
- 1 confusing call to action: email us in sidebar
- Search for “home insurance” fails, top 5 results above the fold are irrelevant and interface is confusing

## Insurance site inspiration / competitor analysis

- [Geico](https://geico.com)
- [TIAA CREF Life Wizard](https://www.tiaa-cref.org/public/products-services/tclife-insurance)
- [Cigna](http://cigna.com)
- [Progressive](https://progressive.com)
- [American Family](https://www.amfam.com)
- [Liberty Mutual](https://libertymutual.com)
- [AXA](https://us.axa.com)
- [Blue Sheild of California](https://blueshieldca.com)
- [Medical Mutual](https://medmutual.com)

## Thoughts

- The main goal of any business marketing site is to convert visitors to paying customers as quickly as possible. We do this by telling a compelling story that is rich, honest, and concise.
- A heavyweight CMS like Joomla or Wordpress isn’t necessary unless you are creating and updating pages and posts every week; a serverless (cloud-based) content editor like [Prose](http://prose.io) or [CloudCannon](http://cloudcannon.com) ($300 billed annually) should be sufficient
- Search functionality isn’t necessary until you reach triple digit pages and posts; the navigation and footer sitemap should be sufficient for visitors who are looking for something specific
- My approach focuses on strong content—validated by business goals—presented with strong visual design fundamentals—typography, layout, and color.
- Need to better understand business goals. [How they make money](http://businessinsure.about.com/od/agentsandbrokers/a/Insurance-Agents-Versus-Brokers-And-How-They-Make-Money.htm)
- I tend to avoid stock photography since it can come across as staged and irrelevant. I once read “when it’s time to tell your story, don’t settle for someone else’s photos.” Why not ask your customers for photos of their business or hire a local photography student to snap some high quality photos at an affordable rate?
- We need to drive traffic to the site with organic search rankings paired with an online advertising budget appropriate for the size of your business. Try starting with Google AdWords with location targeting and 20 paid clicks per day at $0.50 per click ($10/day, ~$300/month). Tweak your keywords and targeting settings every few days throughout the couple months until you learn what works and drives steady leads.

## Agency tooling

- What is the best tool to quickly prove that the site looks as intended on as many devices and browsers as possible? Browserstack?
- What about accessibility? Accessibility auditor browser extension?
- What about A/B testing?

## Content optimizations

- Based on the current number of unique pages and posts, we can bring almost every link to the surface in the footer, then arrange by priority and relevance. A more substantial footer supported by a properly formatted `sitemap.xml` will improve organic search.
- As long as there is a clear distinction between each joke, we can move all 9 Gordie’s Giggles to a single page. More jokes can be added to this page, but Facebook may serve as a better home for this type of content.
- We can remove the _Help Us Celebrate 35 Years_ page because it is no longer relevant.

## Implementation research

- [Group-based navigation structure and active class](http://stackoverflow.com/questions/8340170/jekyll-automatically-highlight-current-tab-in-menu-bar)
- [Categories](http://www.chrisanthropic.com/blog/2014/jekyll-themed-category-pages-without-plugins/)