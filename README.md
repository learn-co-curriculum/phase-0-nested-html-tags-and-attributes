# Nested HTML Tags And Attributes

## Problem Statement

When you take a look at an entire HTML document, it's sometimes challenging to
keep track of where tags begin and end. But understanding more about HTML tag
nesting and attributes can help everything fall into place.

## Objectives

1. Assess HTML document structure
2. Identify nested HTML tags
3. Recognize HTML tag attributes and their purposes

## Nested Tags

Whenever we nest an HTML tag inside of another tag, we indent the inner tag so
that the overall tag hierarchy is clear. Take a look at the following example of
a well-structured HTML document.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Web development course</title>
  </head>
  <body>
    <header>
    <!-- header element documentation: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header -->

      <nav id="main-navigation">
      <!-- nav element documentation: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav -->

        <ul>
        <!-- ul element documentation: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul -->

          <li><a href="/web">Introduction to the web</a></li>
          <!-- li element documentation: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li -->

          <li><a href="/html">Learn HTML</a></li>
        </ul>
      </nav>
    </header>
  </body>
</html>
```

Keeping your HTML well indented so that every tag and "level" of nesting is
aligned will make your code easier to read and maintain.

### HTML Attributes

An HTML attribute is extra information we can add to a tag to identify,
classify, style or modify the default behavior of the element the tag contains.

```html
  <element attribute_name=attribute_value another_attribute_name=another_attribute_value></element>
```
A common use case for HTML attributes is element identification (`id`
attribute) and/or classification (`class` attribute). The `id` attribute is used
to uniquely identify an element within the whole document. The `class` attribute
is used to group together similar elements.

Both `<id>` and `<class>` attributes are often used for styling purposes since
they allow us to find a specific element or style similar elements with a
single style declaration.

```html
  <p id='main_paragraph'>This element can be uniquely identified  using the 'main_paragraph' id HTML attribute</p>
  
  <p class='other_paragraphs'>This element belongs to a group of elements who share the 'other_paragraphs' HTML class attribute</p>
  <p class='other_paragraphs'>This element also belongs to a group of elements who share the 'other_paragraphs' HTML class attribute</p>
```

Attributes that identify or classify are not necessary for the HTML
tag to work as intended, but other attributes *are*—for example, an `a` tag,
which links a piece of text to another location on our own web page or another
web page.

```html
  <a href="https://flatironschool.com/">Flatiron School</a>
```

Here we use the `href` attribute to tell the HTML tag where the destination of
the linked text should be. Without this information, our link won't work and we
won't be able to send more people to the Flatiron School website. Certain
attributes go hand in hand with certain HTML tags, and as you learn the tags,
you'll learn their attributes.

## Resources

* [Nested Tags](http://www.bu.edu/tech/services/cccs/websites/www/non-wordpress/start/html-introduction/syntax/nesting-tags/) More on Nested
* [Tags](https://www.thoughtco.com/nesting-html-tags-3466475) More on Nesting...
* [](http://www.iraqtimeline.com/maxdesign/basicdesign/principles/prinnest.html)
* [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp) More on
* [Attributes](https://www.tutorialspoint.com/html/html_attributes.htm)

## Conclusion

We use nesting to keep the elements of our HTML document organized, and we use
attributes to give our elements more power. With these strategies, we can
construct a solid HTML structure that serves as a foundation for anything else
we want to build.
