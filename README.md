# SimpleHtmlDom

### PHP Simple HTML DOM Parser clone of http://simplehtmldom.sourceforge.net


```
$parser = new \SimpleHtmlDom\Parser();
// get html dom from file
$html = $parser->fileGetHtml("https://www.google.com");

// get html dom from string
$html = $parser->strGetHtml("https://www.google.com");

$html->find("a");
...
```