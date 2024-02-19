# Web Snippets

Collection of standard helper snippets commonly used across web products.


## Social Media Cards

Essential properties:
``` HTML
<meta property="og:title" content="European Travel Destinations">
<meta property="og:type" content="article" />
<meta property="og:image" content="http://euro-travel-example.com/thumbnail.jpg">
<meta property="og:url" content="http://euro-travel-example.com/index.htm">
<meta property="og:description" content="Offering tour packages for individuals or groups.">
<meta property="og:site_name" content="European Travel, Inc.">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image:alt" content="Alt text for image">
```

`og:type` values:

``` HTML
<meta property="og:type" content="article" />
<meta property="og:type" content="website" />
<meta property="og:type" content="profile" />
```



Social Analytics:

``` HTML
<meta property="fb:app_id" content="your_app_id" />
<meta name="twitter:site" content="@website-username">
```

Source: [The Essential Meta Tags for Social Media (CSS-Tricks)](https://css-tricks.com/essential-meta-tags-social-media/)



### Validators:
- [Twitter Cards Validator](https://cards-dev.twitter.com/validator)
- [Meta Sharing Debugger](https://developers.facebook.com/tools/debug/)
- [Google Rich Snippets Testing Tool](https://developers.google.com/search/docs/appearance/structured-data)


### Resources:
 - [The Open Graph protocol](https://ogp.me/)

## SEO Tags

.cshtml:
``` HTML
<meta name="description" content="@ViewBag.MetaDescription" />
<meta name="keywords" content="@ViewBag.MetaKeywords" />
<title>@ViewBag.PageTitle</title>
```

.cs:
``` C#
ViewBag.MetaDescription = "";
ViewBag.MetaKeywords = "";
ViewBag.PageTitle = ""
```
