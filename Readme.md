tableOfPages.js
===========
Simple script, generating a table of available pages in your project.

Usage
===========
Download script.

Add it to yor page and init with list of pages and their description.
```
<script src="scripts/tableOfPages.js"></script>
<script>
  tableOfPages.init({
    "index": "Main page",
    "page1": "Content page 1",
    "foo": "foo bar baz page"
  });
</script>
```

This will add a minimalistic table cantainig links to your pages.
