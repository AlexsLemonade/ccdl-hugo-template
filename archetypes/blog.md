+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
slug = "{{ urlize .TranslationBaseName }}"
author = ""
# Author must be defined as a team member to display correctly
+++

<!--
  The first two paragraphs will be used in the post list.
-->
Paragraph one.

Paragraph two.

<!--
  Everything else will only be shown in the full post.
-->
