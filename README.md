# Week1-Homework
BootCampSpot Web Development - Week 1 Homework

# Notes on Accessiblity
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Accessibility as it pertains to the World Wide Web
primarily revolves around providing equal access and equal opportunity to people with
diverse abilities. Recognized by the UN as a basic human right, the Web supports social
inclusion for people with disabilities, of older generations, and in developing countries.
Their Web traffic makes up an estimated 15%, making Web Accessibility ever important.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; An example of making a webpage accessible is providing
"equivalent alternative text" to images. Alt text can be vital for people who use a screen
reader that reads aloud information on a webpage due to their inability to see. Providing
transcripts for audio files can benefit those who cannot hear, and speech input, in lieu
of having a website rely on mouse input, can benefit those who lack motor control.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; There is also, however, a case for accessibility in terms
of business. This type of accessibility focuses on increasing exposure via mobile web
design, device indepedence, and SEO(Search Engine Optimization) to gain a bigger audience. 

# Motive & Action
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this particular case, our client from a Marketing
Agency wants their website to be optimized for search engines. So, besides code refactoring and
meeting accessibility standards, we will be implemeting SEO to rank higher and distinguish
itself in a search that can yield over a 100 million results. This tends to be a problem
because nearly all online experiences begin with a search engine. While paid searches
come up in the form of ads can be used to appear on the front page, we will look to generate
passive traffic to a website via code.

* HTML:
    - Semantic HTML - Semantic tags added for code readability & organization
    - Codebase follows logical structure
    - Alt attributes added to images as 'alt', element title, or aria-label
    - Element attributes always lead with class
    - Descriptive Webapge Title added

* CSS:
    - Changed class titles as necessary to fit semantic html
    - Arranged classes and grouped by section and sub-sections
    - Grouped duplicate code where possible
    - Tweaked to align main and aside divisions
    - Webpage structure & alignment breaks down at certain browser width thresholds
        - Added different style for viewport widths

* Webpage Accessibliity Standards:
    - Mobile Device Accessibility
        - Change CSS style according to viewport widths less than 640px
    - Social inclusion
        - Disabled
        - Translation
        - Older generation
        - Underpriveliged

* SEO:
    - Title Tag
        - Will show up as the title of the search link
        - Will rank in searches based on similarities to the meta description
            - Must describe website content
        - Makes or breaks your chances of being exposed to the searcher
        - Horiseon - Online Marketing Optimization & Reputation Management 
            - Used keywords and company name
    - Meta Description
        - A quick synopsis of the webpage content
            - Chance to create a selling point
            - Must include keywords used in the Title tag
        - Will appear under the Title Tag search link
    - Header Tags
        - Header Tags will also show up in searches
    - Alt text for images
        - Alt text can also increase chances for exposure
        - Added Horiseon company name to all images
    - Canonical Tag
        - A website will have duplicate webpages
        - Prioritize one webpage to have this single webpage rank higher
        - Linked Canonical Tag - https://www.horiseon.com/
    - Robot Tag
        - If linking out to external website, tag as "nofollow"
        - If trivial pages exist, tag as "noindex"
    - Google Search - Schema Markup
        - Structured Data to help Google find website info
            - Raise chance to appear in Knowledge Graphs
            - Allows for Rich Snippets in search results
        - Make website mobile-friendly for higher rank
        - Use Google Analytics to track keywords
    - Social Media
        - Open Graph Tags
            - Allows webpages to become rich objects in social networks
            - Added OG Title, OG Description, OG Image
        - Twitter Card
            - Open Graph used exclusively for Twitter
            - Added Twitter Card