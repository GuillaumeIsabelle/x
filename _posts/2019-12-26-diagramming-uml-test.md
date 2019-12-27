---
ID: 410
post_title: Diagramming UML Test
author: gicomadmin
post_excerpt: ""
layout: post
permalink: >
  http://guillaumeisabelle.com/x/2019/12/26/diagramming-uml-test/
published: true
post_date: 2019-12-26 20:34:30
---
<!-- wp:paragraph -->

Testing to integrate a diagram

<!-- /wp:paragraph -->

<!-- wp:code -->

<pre class="wp-block-code"><code>[plantuml]
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice &lt;-- Bob: another authentication Response
[/plantuml]</code></pre>

<!-- /wp:code -->