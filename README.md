# Search Engine Optimization (SEO) Basics
The purpose of this website is to touch on the basics of SEO with websites such as these basics:

### Favicon
The Favicon is the little icon next to the title in the tab on the website.
```html
<link href="/favicon.ico?version=0" rel="shortcut icon">
```

### Description
This Description is what appears in the search of the website, under the title.
```html
<meta name="description" content="Whatever you want to say That would appear in search engines.">
```

### Canonical
Allows the Search Engine to specify which URL is important.

```html
<link rel="canonical" href="[Most Improtant Site]">
```

### Language
Language can be set based on who the user is.
`<html lang="en">` - [ISO 639-1 Codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)

### Location
Set the Location of the Website.
```html
<meta name="geo.region" content="US-MI">
<meta name="geo.placename" content="East Lansing">
<meta name="geo.position" content="42.734163;-84.4828162">
```

### Ignore!
Try and allow the website to be ignored from all different robots.
```html
<meta name="robots" content="noindex, nofollow">
```
