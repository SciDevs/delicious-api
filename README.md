# [<img src="https://delicious.com/img/logo.png" alt="Delicious logo" width="28">](https://delicious.com/) Delicious API Documentation

This document and the APIs herein are subject to change at any time. We will version the API, but may deprecate early versions aggressively.

## RSS and JSON feeds

Documentation for feeds of public or private bookmarks can be found here: https://delicious.com/rss


## Keep in Mind

- Please wait **at least one second** between HTTP queries, or you are likely to get automatically throttled. If you are releasing a library to access the API, you **must** do this.
- Please watch for 500 or 999 errors and back-off appropriately. It means that you have been throttled.
- Please set your User-Agent to something identifiable. The default identifiers like `Java/1.4.3` or `lwp-perl` etc tend to get banned from time to time.
- If you are releasing software or a service for other people to use, your software or service **must not** add any links without a user’s explicit direction. Likewise, you **must not** modify any urls except under the user’s explicit direction.
- API calls of Objects returns as an Xml object.

## Authentication

All `/v1` APIs now use [OAuth 2.0](https://github.com/avos/delicious-api/blob/master/api/oauth.md) for authentication.

## Objects

* [Posts](https://github.com/avos/delicious-api/blob/master/api/posts.md)
* [Tags](https://github.com/avos/delicious-api/blob/master/api/tags.md)
* [Tag Bundles](https://github.com/avos/delicious-api/blob/master/api/tagbundles.md)

## Feedback

Contact [feedback@delicious.com](mailto:feedback@delicious.com) if you have any question with using our APIs.
