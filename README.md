# 01-code-refactor
Homework #1 due 9.8

* Link Errors
    * Giving the "search-engine-optimization" section both a class and ID fixed the link to that section

* Semantic Errors
    * Added <header> tag for combined header and nav
    * Changed attribute from class to id for "seo" in header
    * Changed tag from <div> to <content> for "content"
    * Changed tag from <div> to <img> for "hero", changed attribute from class to id
    * Changed tag from <div> to <section> for "search-engine-optimization", "online-reputation-management", and "social-media-marketing"
        * Made sure that "search-engine-optimization" had both class and id attributes for formatting and linking
    * Changed tag from <div> to <aside> for "benefits"
    * Changed tag from <div> to <section> for "benefit-lead", "benefit-brand", and "benefit-cost"
        * Replaced this with one class called "benefit", and added "benefit h3" and "benefit img" with the appropriate styling
        * This removed the need to individually style each section, h3, and img, since they were all the same format
    * Changed tag from <div> to <footer> for "footer
    * In all sections, fixed inconsistency in closure of <img> tags

* Styling Errors
    * Changed image in online-reputation-management to floating left for page consistency

* Alt Attribute Errors
    * Added alt attributes for each image, except for "digital-marketing-meeting" since it's linked as a background image in CSS

* Misc
    * Changed title to "Horiseon Homepage"
    * In CSS, moved all code related to the aside section down below the content to match the html script and page layout