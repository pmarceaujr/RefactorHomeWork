# RefactorHomeWork

This is the Refactor project. Start date: 3/4/2021.

PURPOSE: THe purpose of the project is to refactor/clean-up the existing code to make it more accessible for users that access the site using assistive technologies like video captions, screen readers, and braille keyboards.

OUTPUT: The final output of the project is to submit an improved and refactored site with clean code that still operates as the orginal site.

The follwing items were modified:

- repalce the <title>website</title> with a proper title <title>Horiseon</title>
- replace the <div class="header"> with a semantic <header> section tag
- replace the <div> under the <h1>Hori<span class="seo">seo</span>n</h1> with <nav> tags
- replace the <div class="content"> with smeantic <main> tags
- replace the standard <div class="benefits"> with semantic <aside> tags
- repalce the <div class="footer"> with semantic <footer> tags
- changed the header class select to an element sleect (removed the "." in the CSS file)
- changed the footer from a class selector to an element selector (removed the ".")
- replace "DIV" with "NAV" in the CSS file to support the smemantic tags that were changed in the HTML.
- changed the "DIV" tags in the benefits section and replaced them with smeantic tags of "Benefits" for the aside content and used existing class selectors and repositioned them in the semenatic benenfits tags.
- combined the follwoing selectors into a single group: .benefit-lead, .benefit-brand, .benefit-cost
- combined the follwoing selectors into a single group: .benefit-lead h3, .benefit-brand h3, .benefit-cost h3
- combined the follwoing selectors into a single group: .benefit-lead img, .benefit-brand img, .benefit-cost img
- combined the follwoing selectors into a single group: .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2
- combined the follwoing selectors into a single group: .online-reputation-management img, .social-media-marketing img, .search-engine-optimization img
- combined the follwoing selectors into a single group: .search-engine-optimization, .online-reputation-management, .social-media-marketing
- replaced the .content class selector tag with the new semantic element sleector tag in the CSS file
- converted the "DIV"s in the body to semantic "SECTION" tags

The follwiong items were added:

- added the id select for "search-engine-optimization" to fix the broken link to the section
- added an alt tag to the Search Engine Optimization image: alt="Search Engine optimization"
- added an alt tag to the Online reputation Mangement image: alt="Online Reputation Management"
- added an alt tag to the Social Media Marketing image: alt="Social Media Marketing"
-

The following items were deleted:

link to deployed application:
