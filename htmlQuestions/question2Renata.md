What's the difference between full standards mode, almost standards mode and quirks mode?

We have moved a bit away from needing to declare these modes, but they are ways for a HTML author to tell the browser how fancy of CSS she is writing so the browser could be prepared to read it properly. This was done by including which mode the docuemnt was written inside the <!DOCTYPE> declaration.

As browsers moved towards all opearting with standards, quirks mode alerted the browser to render this page the old way, as to not break anything. And almost standard mode means just that. The document is almost fully compliant with all the implemented standards, with the exception of a few quirks. Full standards mode means the document was written with the latest standards in mind and could be rendered as normal.

When you declare a document to be html5, browsers (by default) will read it in full standards mode.