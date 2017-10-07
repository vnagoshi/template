---
layout: essay
type: essay
title: !important;
date: 2017-10-06
labels:
  - Computer Science
  - Semantic UI
  - CSS
---

Having a visually appealing design is a must for any webpage; most viewers will only view a site’s homepage before deciding whether to stay or bounce. Many web developers thus spend a great deal of time styling their pages, hoping for a reward of higher retention rates for their trouble. What UI frameworks offer web developers are effectively visually appealing page building blocks. These blocks fit well together with one another and let the developer spend less time worrying about the visual appeal of their site. UI frameworks are needless to say complicated, but once you get accustomed to one and all of its quirks, they make writing and styling visually appealing websites significantly easier. The framework I got accustomed to is Semantic UI.

My main gripe with Semantic UI, is that is takes away parts of your control in what feels like some of the most basic sections of your page’s styling, and this made the process of learning it a bit frustrating. Particulars such as font and background colors and font size that are defined in a linked stylesheet are often overridden by Semantic UI’s default behavior; the UI favoring its own default styles over your CSS rules. This is the same behavior that makes Semantic incredibly useful when structuring the page, but it becomes very annoying as a developer when the free agency you have over your page is stripped from you. You can define a Semantic UI theme to gain control over parts of Semantic’s default behavior, but it’s a stopgap solution.

Initially, I found myself thoroughly frustrated with Semantic UI for the above stated reason; however, as I found workarounds for it, my appreciation of Semantic improved greatly. Unfortunately, my first workaround ended up aggravating me just as much as the problem itself, that solution being inline CSS. The inline CSS would take precedent over any CSS changes occurring elsewhere in the page, namely stylesheets, letting me override Semantic’s control, but my code became abhorrent to trace through and read due to all of the “style=’…’” tags littering my html elements. What made it worse was that most of the tags were effectively identical, and thus should have been defined as classes in a custom stylesheet, were it not for Semantic UI overriding said classes, ignoring my styling.

The second workaround, however, worked flawlessly, and became a “why didn’t I think of this sooner?” solution; the solution being the CSS !important rule. Attaching !important to a CSS rule makes the rule the top-level precedent for all elements its attached to, ignoring any other instances of the rule on the element. With this solution, I could define custom classes with the stylings I wanted, then attach !important wherever Semantic UI was taking unwanted control to get my desired styling. Converting my inline CSS to classes utilizing !important made my HTML and CSS much easier to read and far better organized, and I still benefited from all of Semantic UI’s built in structures and stylings as they were needed in my page without surrendering control of the style entirely.

As I said before, my impression of Semantic UI started off rather rocky, but now I find it to be rather fantastic. Semantic simply saves time as you build a website that would have otherwise been spent trying to get a div aligned or centering an image or otherwise screwing with CSS until the page behaves correctly; Semantic does a large portion that for you (provided you know the right classes). And where Semantic falls short, you can fill in your own stylings to get the perfectly behaving responsive website in far shorter time than using raw CSS styling alone.
