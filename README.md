# login-pages
This is a list of URLS that direct to login pages of CLARIN centres.

It is used by [Link Checker](https://github.com/acdh-oeaw/stormychecker) and [Curation Module](https://github.com/clarin-eric/clarin-curation-module) to detect if a URL points to a login page. This way, the Link Checker will not consider a URL that redirects to one in a list as `OK`, but instead as `RESTRICTED ACCESS`, even if the URL returns 200.

If you wish to add your login page URL, just do a pull request with an edit on the `list.txt` file by adding your URL as a new line.
