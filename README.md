# Better-Unduck

DuckDuckGo's bang redirects are too slow. Add the following URL as a custom search engine to your browser. Enables all of DuckDuckGo's bangs to work, but much faster.

```
https://better-unduck.vercel.app/?q=%s
```

## How is it that much faster?

DuckDuckGo does their redirects server side. Their DNS is...not always great. Result is that it often takes ages.

Unduck solves this by doing all of the work client side. Once you've went to https://better-unduck.vercel.app once, the JS is all cache'd and will never need to be downloaded again. Your device does the redirects, not me.

## Why to use Better-Unduck Insted of Unduck?

Better-Unduck uses Startpage as it's default search engine cause it's results are identical to Google's but provides far better privacy.
