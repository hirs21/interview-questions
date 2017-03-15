What's the difference between HTML and XHTML?

HTML
Start tags are not required for every element.
End tags are not required for every element.
Only void elements such as br, img, and link may be “self-closed” with />.
Tags and attributes are case-insensitive.
Attributes do not need to be quoted.
Some attributes may be empty (such as checked and disabled).
Special characters, or entities, do not have to be escaped.
The document must include an HTML5 DOCTYPE.

XHTML
All elements must have a start tag.
Non-void elements with a start tag must have an end tag (p and li, for example).
Any element may be “self-closed” using />.
Tags and attributes are case sensitive, typically lowercase.
Attribute values must be enclosed in quotes.
Empty attributes are forbidden (checked must instead be checked="checked" or checked="true").
Special characters must be escaped using character entities.
XHTML documents must be well-formed