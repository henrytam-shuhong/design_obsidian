
# 

In the video, you started to learn about some of the ways that UX designers can create web pages with accessibility in mind. As a refresher, you should follow the **Web Content Accessibility Guidelines** (WCAG), which explain how to make web content more accessible to people with disabilities. You can explore [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)

on your own to better understand the design standards recommended. To help you get started, let’s explore a few ways to make designs more accessible. 

## **Accessible markup**

There are several ways to markup your designs to make them accessible for users. 

### **Navigation order**

As a reminder, **annotations** are markers placed next to interactive UI elements, like call-to-action buttons, that demonstrate how people using assistive technology will navigate the app or website. In other words, annotations set the order in which a user would tab through items on a website if they use a screen reader or if they use a keyboard, instead of a touchscreen or a mouse. 

Typically, the navigation order of an app or website starts from the upper-left of the screen to the lower-right. It is especially critical to annotate any interactive elements that fall outside of this standard navigation order, or if the user’s initial focus should stray from the first interactive element placed in the upper left of the screen. 

You can use numbers to illustrate the number of key presses, or tabs, from one item to the next. These numbers are shown in green circles in the image below. When the product is in development, engineers use these annotations too, to inform any modifications to the standard navigation order.

![Image of a laptop displaying a website product screen marked with green numbered circles to represent key presses or tabs.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/eN7-JwznSyerF9fgRAzMJA_9b0c73cb0287475c94e791c236a8e3f1_zUcZUPkFiRKlEj9Gj9_aL_RU6ZNvpzqBXnsD0FVv4_5f3i9TNqfN4psW-_dZw_WWxhn8ZYLpuf8_N2gmTMj_w1ksGTE3smnO7B4WMES6RR82L9YPUAi41hU0QZfYD1eyJWbVB-08UXz_Ug2YCppn87soGVnP1kxfBWYS1HsRrpB7yQZnpyg2ZUSBk-cPaw?expiry=1745366400000&hmac=8Ep6iVdscQYDFC6cRAROrK0YMBJUewc_bi92UGYC-Vw)

### Hierarchical headings

As you learned earlier in the certificate program, **hierarchy** is a visual design principle that designers use to order elements on a page and classify them by their level of importance. 

**Headings** are named sections of a page that use different font sizes, which are larger than the body font size. You can use headings to show hierarchy in your designs and help users easily navigate the page.

Headings are written in **HTML**, the language of the internet. Having specific heading tags, like H1, H2, and H3, allows screen readers to interpret the hierarchy of a page for users. The H1 tag indicates that a particular heading is the most important on the page and is often used for titles. An H2 tag is often used for subtitles or callout boxes. Additional tags, like H3, can also be used to further indicate the hierarchy of the page. The image below shows a wireframe of a website with heading tags. 

![Illustration of a website page with text shows heading tags H1, H2, H3 to indicate the hierarchy of a page example.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dYtnmnIZTQm-VbvwPmHiog_ca32489aa3b741069d169fe409da70f1_nFiyaRgGcQsVk5Hmm5VPwK16v_6owXzY--At0Yv04A-u6rthjozkxuqnRP90KUy5O2ZK0ZqGAdhQUZJS2KDXaAgZzZ3AL9Jzo4BMOmC1LodOWvkn8InGiM6Xik6YiSlhnUeLFJJ-HQh9srB7Q7Z-8d3Qx3Qu_qydJjNevx9AIvMps6MDCWXYAZlqKDa-g?expiry=1745366400000&hmac=M0wBtMfUVgsnlFZZcQKB-YQetgyzYD-ZdSA6wqV7PY0)

### Accessibility labels

**Labels**, or screen reader verbalizations, add descriptive language to the interactive UI elements on the web page. With a label, there can be no doubt about the purpose of the button, menu, or checkbox. For example, a label might read “When the user clicks the checkbox, select the item.” Check out additional examples of labels that a screen reader should read aloud for each button in the image below. 

When annotating labels for interactive elements on your web site designs, note where similar controls should be grouped to provide more efficiency and context. For example, consider grouping a list of checkboxes so that a user of assistive technology could understand the relationship of the checkboxes and how to quickly navigate to and from them. 

Engineers use these labels to determine the best implementation for the experience you are trying to accomplish. 

![Illustration of three UI elements from a web page – “Search”, “My calendars” button and “My calendars” checklist.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/h4JxtxObSzKSQojJU4Suzw_c84f0cd3d5b14403bd67fbbdd7bca3f1_GmjTqo51-p0iXnc7uVNuvro3jat0QsK-1OK4WWc8cVVr--5ev4AkqKms6t_pbBOvGFNlT1_QLIGIDzwRzbCNdIqJ5OR8f9dx8lKHhGy_2JuwCpgbYGoX8rXeunJmesmq6VmdaYBjtFC66qh8Lxu_c8GPnH7nLnax2-fgicjkgNJ98OE7aWE6T8ecGwDStw?expiry=1745366400000&hmac=lc4Cm6kHCTYnrQiKscpAapH2RlBRXIMD3lwc_niRgc0)

Each element is labeled with a description for Accessibility labels, Semantic roles, and Notes.

To keep learning, check out this article from Medium about [annotating your design work](https://medium.com/wayfair-design/design-basics-annotating-your-work-6eac0562097f)

and this article from WebAIM that provides [an introduction to Accessible Rich Internet Applications (ARIA)](https://webaim.org/techniques/aria/)

.

## **Accessible color and contrast**

In an earlier course of the certificate program, you learned how to implement color and contrast to ensure they align with accessibility guidelines. Remember learning the term **luminosity contrast ratio**? It’s a measurement of the contrast between the background of a design and the text color used with it. In short, your designs will be more accessible if you choose a light background with a dark text, or a dark background with a light text.

Additionally, you need to carefully consider the color combinations you choose for your designs. People who are colorblind may experience difficulties differentiating between certain color combinations, like red-green. Plus, many people, especially those who have low contrast sensitivity, may not be able to distinguish individual shapes if the color combinations are too similar, like light gray and white. When choosing colors, you can reference the [WebAIM contrast and color requirements](https://webaim.org/articles/contrast/)

to ensure your designs meet accessibility standards.

Still have questions? Revisit this reading about [accessibility considerations for color](https://www.coursera.org/learn/high-fidelity-designs-prototype/item/Ca3gb)

for a refresher. 

## **Make responsive websites accessible**

As you design a responsive website that adapts to different screen sizes, you need to make sure that all versions of your website are accessible. For example, if users zoom in on an element or increase the size of the font to meet their vision needs, the rest of the page should automatically resize and rearrange to fit the new screen size. Otherwise, when a user enlarges a section of the page, elements might overlap each other. 

In the image below, notice how the screen should adapt when a user zooms in, as compared to a responsive website that does not resize and text becomes unreadable. 

![Illustration of three views of the same website page. On the left is the unzoomed view labeled “Original”.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/rM2Ymu3rSrqVBtLSdSohHw_cd56e50c55574810961b12a0e3c841f1_tpv0eVFsth8xUBCVQtvdpwd6j4Zl2e2Vr8CMTbfOTUK6-Pufv-FO2bblGoJVrffUKgHI2_YPOxcDX5gqwDIfKyjHyfZgVWCJ1D97wRIXZaBQGUGUByOueKGL0Vl03FNnuo8MOtyW6eS1fBqZXsCX51IX7N46lUwOklgk_PEznlU04L_GC3ocVH4oCFlOJQ?expiry=1745366400000&hmac=yosQCB7DdRcSee0_HzWojzvz5eVrhNTCX7ech9YBpJc)

The second image shows a zoomed in view that is readable and labeled with a check mark. The third image is zoomed in and unreadable labeled with a red “X”.

It’s critical to communicate these different interactions to engineers. For example, it’s helpful to create multiple versions of your mockups: one to show the designs at the default display and text settings, and another to show the enlarged (or zoomed in) display. That way, you can take magnification and other responsive design requirements into account before the website is fully developed.

## **Additional resources**

There’s a lot more to learn when it comes to designing accessible websites. Check out this page about [designing with accessibility in mind](https://m3.material.io/foundations/accessible-design/overview)

on Google’s Material Design website, which includes guidance about hierarchy, color, layouts, and more. In addition, explore [The A11Y Project](https://www.a11yproject.com/), a collection of resources from designers across industries that was created to make digital accessibility easier.