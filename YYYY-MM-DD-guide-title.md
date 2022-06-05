---
layout: post # Don't change this
title: Official Title Of Your Guide # change this

# delete one of the submitted_by fields
submitted_by: "FirstName LastName" # change this, keep the quotation marks
submitted_by: "[FirstName LastName](https://mywebsite.com)" # Use this format if you want to link your website, keep the quotation marks

edited_by: # add your name if you modified a document (not necessary for new guides)
---
<button><a href="/guides">Back to all Guides</a></button>

Submitted by: {{ page.submitted_by }}

{% if page.edited_by != null %}
Edited by: {{ page.edited_by }}
{% endif %}

<!-- Your content here in MarkDown or HTML format (Jekyll can handle a mix of both!) -->

<button><a href="/guides">Back to all Guides</a></button>
