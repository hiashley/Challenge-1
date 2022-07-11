# Challenge 1

## Description

I refactored the HTML and CSS code to achieve web accessiblity. It needed to be more accessible to those with disablities. It would also rank higher in search engines, delivering more traffic to the site and having better search engine optimization.

## HTML Changes
- Added Comments labeling the groups of semantic elements (i.e., header, footer, main, etc).
- Changed title from *website* to *Horiseon Homepage*
- Replaced `div` elements to semantic elements and deleted the class names **header**, **contents**, **benefits**, and **footer**.
  - `header`, `nav`, `main`, `img`, `article`, `section`, `aside`, and `footer`
- Added `alt` and `title` attributes to the image elements
- Added and `id` **search-engine-optimization** so that clicking the link *Search Engine Optimization* on the navigation bar would direct to the associated section.
- Changed and condensed the `class` names **search-engine-optimization**, **online-reputation-management**, and **social-media-marketing** to **article-section** as they had the same exact properties.
  - Same changes made: **benefit-lead**, **benefit-brand**, and **benefit-cost** to **aside-section**

## CSS Changes
- Changed the classes `.header`, `.div`, `.content`, `.benefits`, `.footer` to semantic elements in the css instead. For instance instead of the class `.header` it would be the html element `header` in css.
- As mentioned in **HTML Changes**, I condensed the classes in the article sections and aside sections to single classes so as to not repeat multiple lines of css.
- I restructured the css in a way that the elements would follow a logical and hierarchical  structure.
  - i.e., all the attributes under the header tag would be grouped together, and attributes under the aside tag would also be grouped together (I labeled these groups with comments in the css).
- The `class` `.hero` had the property **background-image: url("../images/digital-marketing-meeting.jpg");**. Instead, I rid of the `div` in html and replaced that with an actual `img` tag and linked the image in html. I then deleted said property in css.

## Screenshot
![Website Screenshot](./assets/images/website-screenshot.png)

## Link
[Deployed website](https://hiashley.github.io/Challenge-1/)
