_____________________________________________________________________________________________________________________________________

Headers : 

# This is an <h1> tag
## This is an <h2> tag
### This is an <h3> tag
#### This is an <h4> tag
##### This is an <h5> tag
###### This is an <h6> tag

_____________________________________________________________________________________________________________________________________

Emphasis: 

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

_____________________________________________________________________________________________________________________________________

Lists

Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b

Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

_____________________________________________________________________________________________________________________________________


Images

Format: ![Alt Text](url)
Eg.   ![GitHub Logo](/images/logo.png)

_____________________________________________________________________________________________________________________________________

Links

Format : [Alt text](url)
[GitHub](http://github.com)

_____________________________________________________________________________________________________________________________________


GitHub Flavored Markdown

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it
easier to work with content on GitHub.com.

Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

_____________________________________________________________________________________________________________________________________


Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

_____________________________________________________________________________________________________________________________________


Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
Would become:
_____________________________________________________________________________________________________________________________________

SHA references
Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

_____________________________________________________________________________________________________________________________________

Issue references within a repository
Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1

_____________________________________________________________________________________________________________________________________

Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.
_____________________________________________________________________________________________________________________________________

Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

_____________________________________________________________________________________________________________________________________

Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

_____________________________________________________________________________________________________________________________________

Emoji
GitHub supports emoji!
To see a list of every image we support, check out the Emoji Cheat Sheet.

_____________________________________________________________________________________________________________________________________
