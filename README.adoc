# Zimbra Technical Overview

Building the Documentation
--------------------------

The Zimbra Technical Overview Guide is written using
link:http://asciidoc.org/[AsciiDoc]. Specifically, it is intended to be
processed with link:http://asciidoctor.org/[Asciidoctor].

As a prerequisite to building the documentation, you will need to have
already installed and configured
link:http://asciidoctor.org/[Asciidoctor]. Check the
link:http://asciidoctor.org/docs/user-manual/#installation-quick-start[Installation
Quick Start] in the
link:http://asciidoctor.org/docs/user-manual/[Asciidoctor User Manual] for
information on how to get started.

Once you have Asciidoctor installed and working, you can build the
documentation into HTML files like so:

[source,bash]
----
asciidoctor -b html5 -a stylesheet=images/foundation.css proposal.adoc
----

Each section of the document is contained in its own file. You may use the
`proposal.adoc` file to generate the entire document.

For PDF,

[source,bash]
----
asciidoctor-pdf -a pdf-stylesdir=themes -a pdf-fontsdir=themes -a pdf-style=custom proposal.adoc
----

Additional Information
----------------------

Visit https://www.zimbra.com[*www.zimbra.com*] to join the community and to
be a part of building the best open source messaging solution. We
appreciate your feedback and suggestions.

Join the https://forums.zimbra.org/[Zimbra Forums], to participate and
learn more about Zimbra.

For additional product information check the https://wiki.zimbra.com[Zimbra Wiki].
