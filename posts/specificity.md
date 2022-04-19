---
title: Specificity
description: This is a post on My Blog about Specificity.
date: 2022-04-18
tags:
  - CSS
layout: layouts/post.njk
---
Specificity determines the order in which rules are given priority when changing CSS styles in an HTML page. There are four ranks in which CSS code is given priority. Top priority is Inline CSS Styling, which is when you apply the style code inside the HTML code, such as if you have `<p style="color: blue">` that is an example of Inline CSS. Inline CSS is generally frowned upon as it overrides everything else and is very rigid in customization and may block the ability to target specific elements or classes within a code-block. The second to highest priority is using code ID's, with the 3rd being classes and last being elements.
	Ideally, a developer should try to create classes and target elements when styling in CSS, using Internal CSS or External CSS, to keep code clean, and be able to target specific code in your HTML. Another thing to remember is that each level of priority is only relevant to that level. For example, you can have an infinite number of ID's used to create styles in your HTML, but if you use inline CSS styling, it will override all the ID's. So it's important to understand the heirarchy. If you use 5 ID's to change a style to an HTML code it will override a style code that used 4 ID's. 