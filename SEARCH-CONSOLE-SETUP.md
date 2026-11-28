# Google Search Console setup

The site is prepared for Google Search Console, but ownership verification and sitemap submission must be completed from the site owner's Google account.

1. Open [Google Search Console](https://search.google.com/search-console/).
2. Add the Domain property for `annabelleklosterman.com` if it is not already present. Domain properties require DNS verification. Follow Google's current instructions and add the TXT record it provides at the domain's DNS host. Do not use a guessed verification token.
3. If you prefer URL-prefix verification, add `https://www.annabelleklosterman.com/` and choose an available verification method. For an HTML tag or HTML file method, place Google's exact supplied token or file in the repository. Do not edit the token.
4. Once ownership is verified, open **Sitemaps** and submit:

   `https://www.annabelleklosterman.com/sitemap.xml`

5. Use **URL Inspection** for the homepage, resource center, and each article. Run a live test, then request indexing where appropriate.
6. Revisit the **Pages** and **Performance** reports over the following weeks. Indexing and search visibility are not immediate and are not guaranteed by submitting a sitemap.

## Canonical domain

The repository's GitHub Pages `CNAME` file names `www.annabelleklosterman.com`, so all canonical URLs and sitemap entries use that HTTPS hostname.
