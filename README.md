# Bookmarklets-Zoo

This is fancy collection of various bookmarklets. And also teach you how to write your own bookmarklet.

Currently, I am working on a browser add-in that can arrange and collect the bookmarklet you favored. It also provides a graphic interface to create bookmarklets easily. If you like this, please light up a star🌟 for this repo. Moreover, if you have some ideas on bookmarklets, or you find error & typo in this repo, feel free to put forwards an issue. Thanks for your contribution!

## Bookmarklet

What is a bookmarklet?

A bookmarklet is a bookmark stored in a web browser that contains JavaScript commands that add new features to the browser. Bookmarklets are unobtrusive JavaScripts stored as the URL of a bookmark in a web browser or as a hyperlink on a web page. Bookmarklets are usually JavaScript programs. Regardless of whether bookmarklet utilities are stored as bookmarks or hyperlinks, they add one-click functions to a browser or web page. When clicked, a bookmarklet performs one of a wide variety of operations, such as running a search query or extracting data from a table. For example, clicking on a bookmarklet after selecting text on a webpage could run an Internet search on the selected text and display a search engine results page.

## Deploy Bookmark

It is really simple to deploy a bookmarklet. If you want to put it on your own website, you can insert a javascript line in the source code of your web page, like:
```html
<a href="javascript:alert('give my repo a star!');">xxx</a>
```
For daily user, you can drag the link in the browser's address line, or copy the link into your favorites. Anytime you want to use it, just give it a click.

### Restrictions
In fact, bookmarklets can be treated as URLs, just in different forms. So those restrictions on the URLs are also valid on bookmarklets.

- The length of it are limited. Some old browser like IE can only support strings of around 2,000 characters, while modern browser like Chrome support strings of around 8,000 characters. The limited length affects your code.
- Just like URLs, bookmarklet should be in only one line. In addition, some browsers don't support space between character. So, your code should be something like `yourcodenospace`.

Good news is, we have some tricks to fix these problems elegantly.