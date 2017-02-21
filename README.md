# \<paper-weather\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ryanburns23/paper-weather)

Material design weather element inspired by google weather

No api key required

- Weather data:
[Yahoo Weather API](https://developer.yahoo.com/weather/)

- Weather icons by [Naman Rastogi](https://material.uplabs.com/posts/google-now-weather-icons-freebie)

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-weather.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-weather location="Santa Barbara, CA"></paper-weather>
```

### Rate limits

Without an API Key:
- Hourly Cap	2,000 requests/hour per IP
- Daily Cap	None

If you register a yahoo API key you get up to 20,000 requests/hour per IP [More info](https://developer.yahoo.com/yql/guide/usage_info_limits.html)
