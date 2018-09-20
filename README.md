# HTML Iframes

## Problem Statement

At some point in your journey, you likely be asked to embed code from a
different website into the one you are building. This can be done for something
less complicated like displaying a Google search bar, to a Youtube video, to
more complex tasks like a Google Map that displays your users exact location.
This is achieved by using HTML iframes. 


## Objectives
1. Describe how iframe elements work
2. Embed a map element into an existing HTML page

## Describe How Iframe Elements Work

Iframe elements allow us to link to other HTML content from within a frame
window on our pages. 

Iframe elements have one required attribute: `src`. The `src` attribute takes a
link and displays the page requested. The `src` attribute points to the location
of other HTML content and displays it within the current page. 

You can also specify multiple different non-required elements, such as `width`,
`height`, `frameborder`, `allowfullscreen`, and `style`.

 
## Embed a map element into an existing HTML page
To embed a map into a webpage, you can use the Google Maps Embed API URL as the `src` attribute for your iframe:
```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d335994.89219194185!2d2.0673752159642937!3d48.8589713267984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e1f06e2b70f%3A0x40b82c3688c9460!2sParis%2C+France!5e0!3m2!1sen!2sus!4v1457911182825" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d335994.89219194185!2d2.0673752159642937!3d48.8589713267984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e1f06e2b70f%3A0x40b82c3688c9460!2sParis%2C+France!5e0!3m2!1sen!2sus!4v1457911182825" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

*Top Tip: To embed a Google Map, you must first [request a free API key](https://developers.google.com/maps/documentation/embed/get-api-key).*


## Conclusion 
Iframes are powerful tools that allow us to show content from one website within
a different site. You can iframe any website you'd like, but certain sites make
more sense to iframe than others. Iframing search sites and mapping sites is
most common, but use your imagination to be creative and play around with all
kinds of iframes!

## Resources 
- [HTML Forms and Iframes](https://www.youtube.com/embed/eiCtXc2YMKc?rel=0)
- [Presentation Slides](https://docs.google.com/presentation/d/115ECvsMyDnFBcc-Rvb4Jn876JhOycXxKVN6sv7OiJ1Y/edit?usp=sharing)
- [MDN - HTML - Iframe](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)
- [Google Maps iframe documentation](https://developers.google.com/maps/documentation/embed/guide)