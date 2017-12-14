# Nested Tags And Attributes

### Nested Tags

Tags can be nested as demonstrated in the navigation snippet below.

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

Keeping your HTML well indented so that every tag and "level" of nesting is aligned will make your code easier to read and maintain. Its aesthetics, how it looks, is conveying its structure.

### HTML Attributes
HTML attributes represent metadata about the containing element.  The attributes can be used to identity, classify, style or modify the default behavior of the element.

HTML attributes are key, value pairs combinations added to the element's opening tag.

```html
	<element attribute_name=attribute_value another_attribute_name=another_attribute_value></element>
```

A very common use case for HTML attributes is element identification (`id` attribute) and/or classification (`class` attribute). The `id` attribute is used to uniquely identify an element within the whole document. The `class` attribute is used to group together similar elements. 

Both `<id>` and `<class>` attributes are often used for styling purposes since they allows us to find a specific element or style similar elements with a single style declaration.

```html
	<p id='main_paragraph'>This element can be uniquely identified  using the 'main_paragraph' id HTML attribute</p>
	
	<p clas='other_paragraphs'>This element belongs to a group of elements who share the 'other_paragraphs' HTML class attribute</p>
	<p clas='other_paragraphs'>This element also belongs to a group of elements who share the 'other_paragraphs' HTML class attribute</p>
```

## Resources

* [Nested Tags](http://www.bu.edu/tech/services/cccs/websites/www/non-wordpress/start/html-introduction/syntax/nesting-tags/)
* [More on Nested Tags](https://www.thoughtco.com/nesting-html-tags-3466475)
* [More on Nesting...](http://www.iraqtimeline.com/maxdesign/basicdesign/principles/prinnest.html)
* [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)
* [More on Attributes](https://www.tutorialspoint.com/html/html_attributes.htm)
