# Web Snippets

Collection of standard helper snippets commonly used across web products.


## Social Media Cards

Essential properties (HTML):

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

`og:type` values (HTML):

``` HTML
<meta property="og:type" content="article" />
<meta property="og:type" content="website" />
<meta property="og:type" content="profile" />
```

Essential properties (CSHTML):

```HTML
<meta property="og:title" content="@ViewBag.OgTitle">
<meta property="og:type" content="@ViewBag.Type" />
<meta property="og:image" content="@ViewBag.OgImage">
<meta property="og:url" content="@ViewBag.OgUrl">
<meta property="og:description" content="@ViewBag.OgDescription">
<meta property="og:site_name" content="@ViewBag.OgSiteName">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image:alt" content="@ViewBag.TwitterImageAlt">
```

Essential properties (C#):

```
ViewBag.OgTitle = "";
ViewBag.Type = "";
ViewBag.OgImage = "";
ViewBag.OgUrl = "";
ViewBag.OgDescription = "";
ViewBag.OgSiteName = "";
ViewBag.TwitterImageAlt = "";
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

Essential properties (HTML):

```HTML
<meta name="description" content="Meta description" />
<meta name="keywords" content="Meta keywords" />

<title>Page title</title>
```

Essential properties (CSHTML):

```HTML
<meta name="description" content="@ViewBag.MetaDescription" />
<meta name="keywords" content="@ViewBag.MetaKeywords" />

<title>@ViewBag.PageTitle</title>
```

Essential properties (C#):

```
ViewBag.MetaDescription = "Meta description";
ViewBag.MetaKeywords = "Meta keywords";
ViewBag.PageTitle = "Page title";
```
