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

<!-- wp:paragraph -->

Bellow is using a normal paragraph

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

  
[plantuml]  
GI --> WPApp : Capture source to web  
GI --> Zotero : Capture source to ref  
WPApp --> Zotero : Reference the captured ref  
[/plantuml]

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

  


<!-- /wp:paragraph -->

<!-- wp:paragraph -->



<!-- /wp:paragraph -->

<!-- wp:separator -->

<hr class="wp-block-separator" />

<!-- /wp:separator -->

<!-- wp:paragraph -->

Bellow is using a Shortcode...

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [plantuml] Alice -> Bob: Authentication Request Bob --> Alice: Authentication Response Alice -> Bob: Another authentication Request Alice <-- Bob: another authentication Response [/plantuml] 

<!-- /wp:shortcode -->