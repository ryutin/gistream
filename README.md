# gistream

1. list of text news sites
 * http://www.csmonitor.com/layout/set/text/textedition
 * https://twitter.com/breakingnews
 * http://www.nationalpost.com/m/index.html
 * http://mobile.reuters.com/
2. dump news as text
 * ```
lynx -nolist -dump "http://www.nationalpost.com/m/wp/news/blog.html?b=news.nationalpost.com/news/world/matthew-fisher-scheming-putin-to-arm-kurds-with-advanced-weapons-despite-canadas-olive-branch&pubdate=2016-04-24"
```
3. Parse via Calais
 * get "social tags" and link with Wikipedia
 * extract geographics from "Topics"
 * create key from "Topics" to track event trends
4. Create map with link of regions to news
