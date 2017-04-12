Why is it generally a good idea to position CSS <link>s between <head></head> and JS <script>s just before the end body tag? Do you know any exceptions?

CSS should be loaded in the head section to so that styling can be loaded before the page body loads, else the page will appear without styling.

JS should be loaded after all content has loaded, ie just before the closing body tag, so that loading of possibly large JS files does not initial page load.

An exception would be Modernizr, which detects support for various features and adds classes saying whether they are supported to the html tag. And those classes are used for styling which is why they should be added as soon as possible.
