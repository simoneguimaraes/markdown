# GitHub Markdown

## What is Markdown?
Markdown is a way to style text on the web. You control the display of the document; formatting words as **bold** or *italic*, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

## Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

### Headers
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

### Inline code
You can highlight something, like a tag `<html>`
```
You can highlight something, like a tag `<html>`.
```

### Links
http://github.com - automatic!
```
http://github.com
```

Or:
[GitHub](http://github.com)
```
[GitHub](http://github.com)
```

### Emphasis
*This text will be italic*
```
*This text will be italic*
_This will also be italic_
```

**This text will be bold**
```
**This text will be bold**
__This will also be bold__
```

### Lists
#### Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
```
- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
```

#### Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

### Blockquotes
As Kanye West said:
> We're living the future so
> the present is our past.
```
> We're living the future so
> the present is our past.
```

### Images
If you want to embed images, this is how you do it:
Format: `![Alt Text](url)`
```
![Cute Dog](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTZlxSynjnFPJD7hAe0LhUsjQVVRpZYa3Ve9g&usqp=CAU)
``` 
![Cute Dog](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTZlxSynjnFPJD7hAe0LhUsjQVVRpZYa3Ve9g&usqp=CAU)


### GitHub Flavored Markdown

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

#### Syntax highlighting
Here’s an example of how you can use syntax highlighting with <a href='https://help.github.com/articles/basic-writing-and-formatting-syntax/'>GitHub Flavored Markdown</a>:

It will apear like this:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```


``` 
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}```
```

You can also simply indent your code by four spaces:
```
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
```

Here’s an example of Python code without syntax highlighting:
```
def foo():
    if not bar:
        return True
```

#### Task Lists
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

#### Tables
You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

#### Emoji
GitHub supports <a href='https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji'>emoji</a>!

To see a list of every image we support, check out the <a href='https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md'>Emoji Cheat Sheet</a>. 

#### Username @mentions
Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

#### Strikethrough
Any word wrapped with two tildes (`~~this~~`) will appear crossed out. Like this: `~~this~~`

#### SHA references
Any reference to a commit’s <a href='http://en.wikipedia.org/wiki/SHA-1'>SHA-1 hash</a> will be automatically converted into a link to that commit on GitHub.

```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

#### Issue references within a repository
Any number that refers to an Issue or Pull Request will be automatically converted into a link.
```
#1
mojombo#1
mojombo/github-flavored-markdown#1
```

You can use Markdown most places around GitHub:

* <a href='https://gist.github.com/'>Gists</a>
* Comments in Issues and Pull Requests
* Files with the `.md` or `.markdown` extension

For more information, see <a href='https://help.github.com/categories/writing-on-github/'>“Writing on GitHub”</a> in the *GitHub Help*.

To read the complete article: https://guides.github.com/features/mastering-markdown/
