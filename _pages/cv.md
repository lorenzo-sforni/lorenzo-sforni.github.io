---
layout: none
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: cv.pdf
---
<html>
  <head>
    <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width">
  </head>
  <body>
    <object data="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}" type="application/pdf" style="min-height:100vh;width:100%"></object>
  </body>
</html>