# <a href="http://wsphynx.com/index.html">WSphynxJS</a>


<a href="http://wsphynx.com/index.html">WSphynxJS</a> is a Javascript and HTML library for building powerful interfaces.


Key features of WSphynxJS:

* Clarify:

    WSphynxJS allows you to organize your HTML code. You will be able to write events or scripts which interact with a specific div.

* Simple to use:

    WSphynxJS uses a usual syntax. It is easy to learn and to use. You just have to add the prefix "ws".

* Design:

    A modern design to enhance your code. The library is developed with a powerful syntax to match with the most recent browsers.
    
<a href="http://wsphynx.com/docs.html">Learn WSphynxJS</a>

# <a href="http://wsphynx.com/docs.html">Installation</a>

It is possible to use WSphynxJS thanks to a `script` tag placed in the `head` part:

```html
<head>
  <!--Some stuff here-->
  <script defer src="http://wsphynx.com/simple(1.0).txt"></script> 
</head>
```

You can also directly download the library <a href="http://wsphynx.com/simple(1.0).txt">here</a>. However, we do not recommend to copy the code in your own web page. We often update the source code and you would probably miss new functionalities or bug corrections.

<a href="http://wsphynx.com/docs.html">Getting started</a>

# Simple example

```html
<wsdiv> Hello
    <wsonmousedown>
        element.textContent = "Clic";
    </wsonmousedown>
    <wsonmouseup>
        element.textContent = "Up";
    </wsonmouseup>
</wsdiv>
```

This example will render a simple `div` saying Hello. When you clic on it the div displays "Clic" and when you release the mouse it displays "Up".

With WSphynxJS, you can declare dynamic events and interact with your HTML page more easily.

# License

<a href="http://wsphynx.com/about.html">WSphynxJS is MIT licensed</a>.
