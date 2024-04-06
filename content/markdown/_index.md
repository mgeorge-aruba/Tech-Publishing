---
type: docs
title: Markdown Examples
linkTitle: Markdown Examples
weight: 1000
description: |
  Markdown examples in action
simple_list: false
resources:
  - src: "**library*"
    params:
      byline: "*Photo*: Bjørn Erik Pedersen / CC-BY-SA"
draft: true
---

{{% alert title="Draft Status" color="info" %}}
This page is marked as a draft and as such should not be rendered at the server.
{{% /alert %}}

Text can be normal, **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](/docs/).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs.

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
Text can be normal, **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](/docs/).

[Link to another page using relref]({{</* relref "base-dir/path" */>}})

There should be whitespace between paragraphs.

There should be whitespace between paragraphs.
{{< /card >}}

## Headings in the document start at header 2

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

### Header 3

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.
{{< /card >}}

#### Header 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

##### Header 5

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

###### Header 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Lists

Ordered (numbered) and unordered (bulleted) lists

### Unordered list

- This is an unordered list following a header.

- This is an unordered list following a header.

- This is an unordered list following a header.

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- This is an unordered list following a header.

- This is an unordered list following a header.

- This is an unordered list following a header.
{{< /card >}}

### Ordered list

1. This is an ordered list following a header.

2. This is an ordered list following a header.

3. This is an ordered list following a header.

An ordered list without specifying the ordinals, allowing automatic renumbering:

1. Item one

1. Item two

1. Item three

1. Item four

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
1. This is an ordered list following a header.

2. This is an ordered list following a header.

3. This is an ordered list following a header.

An ordered list without specifying the ordinals, allowing automatic renumbering:

1. Item one

1. Item two

1. Item three

1. Item four
{{< /card >}}

### Ordered list, continued

{{% alert title="Warning" color="warning" %}}
Not available or working currently.
{{% /alert %}}

1. Item one
1. Item two

Some text

1. Item three
1. Item four
{style="counter-reset:none;"}

An ordered list starting from 42:

{style="counter-reset:step-counter 41"}

1. Item 42
1. Item 43
1. Item 44

### And a multi-level/nested list

- level 1 item

  - level 2 item

  - level 2 item

    - level 3 item

    - level 3 item

- level 1 item

  - level 2 item

  - level 2 item

  - level 2 item

- level 1 item

  - level 2 item

  - level 2 item

- level 1 item

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- level 1 item

  - level 2 item

  - level 2 item

    - level 3 item

    - level 3 item

- level 1 item

  - level 2 item

  - level 2 item

  - level 2 item

- level 1 item

  - level 2 item

  - level 2 item

- level 1 item
{{< /card >}}

### Nesting an ol in ul

Nesting of mixed lists types only goes one deep

- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)

- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)

- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)

- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)

- level 1 item (ul)

  1. level 2 item (ol)

  1. level 2 item (ol)
{{< /card >}}

### And a task list

- [ ] Hello, this is a TODO item

- [ ] Hello, this is another TODO item

- [x] Goodbye, this item is done

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- [ ] Hello, this is a TODO item

- [ ] Hello, this is another TODO item

- [x] Goodbye, this item is done
{{< /card >}}

### Nesting task lists

- [ ] level 1 item (task)

  - [ ] level 2 item (task)

  - [ ] level 2 item (task)

- [ ] level 1 item (task)

- [ ] level 1 item (task)

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- [ ] level 1 item (task)

  - [ ] level 2 item (task)

  - [ ] level 2 item (task)

- [ ] level 1 item (task)

- [ ] level 1 item (task)
{{< /card >}}

### Nesting a ul in a task list

- [ ] level 1 item (task)

  - level 2 item (ul)

  - level 2 item (ul)

- [ ] level 1 item (task)

- [ ] level 1 item (task)

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- [ ] level 1 item (task)

  - level 2 item (ul)

  - level 2 item (ul)

- [ ] level 1 item (task)

- [ ] level 1 item (task)
{{< /card >}}

### Nesting a task list in a ul

- level 1 item (ul)

  - [ ] level 2 item (task)

  - [ ] level 2 item (task)

- level 1 item (ul)

- level 1 item (ul)

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
- level 1 item (ul)

  - [ ] level 2 item (task)

  - [ ] level 2 item (task)

- level 1 item (ul)

- level 1 item (ul)
{{< /card >}}

## Overflow behaviors

[This is a very long link (Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.) which wraps and therefore doesn't overflow even when it comes at the beginning](.) of the line.

- [This is a very long link (Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.) which wraps and therefore doesn't overflow the line when used first in an item](.) in a list.

## Table

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |
| unordered lists in cells | <ul><li>HTML</li><li>Required</li></ul> | possible |
| ordered lists in cells | <ol><li>HTML</li><li>Required</li></ol> | possible |

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |
| unordered lists in cells | <ul><li>HTML</li><li>Required</li></ul> | possible |
| ordered lists in cells | <ol><li>HTML</li><li>Required</li></ol> | possible |
{{< /card >}}

## There's a horizontal rule below this

* * *

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
* * *
{{< /card >}}

## Images

Setting a byline requires defining a resource and the byline in the frontmatter

### Small image

{{% imgproc library Resize 200x %}}
Wroclaw University Library digitizing rare archival texts
{{% /imgproc %}}

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
{{%/* imgproc library Resize 200x */%}}
Wroclaw University Library digitizing rare archival texts
{{%/* /imgproc */%}}
{{< /card >}}

### Large image

{{% imgproc library Fit 600x600 %}}
Wroclaw University Library digitizing rare archival texts
{{% /imgproc %}}

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
{{%/* imgproc library Fit 600x600 */%}}
Wroclaw University Library digitizing rare archival texts
{{%/* /imgproc */%}}
{{< /card >}}

## Callouts

Callouts are enabled by using the `alert` shortcode. The title of a callout is specified in the `title` field of the shortcode, with the color of the shortcode being optional.

```go-html-template
{{%/* alert title="<title for the callout>" color="<color from theme>" */%}}
This is a generic callout that uses the specified coloring.
{{%/* /alert */%}}
```

{{% alert title="Callout" %}}
This is a generic callout that has color unspecified so uses the primary coloring.
{{% /alert %}}

{{% alert title="Note" color="info" %}}
This is a note callout, specifying the `info` color. [Example of a link](#callouts)

```go-html-template
code block for testing
this is inside a callout
interesting results
```
{{% /alert %}}

{{% alert title="Warning" color="warning" %}}
This is a warning callout, specifying the `warning` color. [Example of a link](#callouts)

```go-html-template
code block for testing
this is inside a callout
interesting results
```
{{% /alert %}}

{{% alert title="Danger" color="danger" %}}
This is a danger callout, specifying the `danger` color. [Example of a link](#callouts)

```go-html-template
code block for testing
this is inside a callout
interesting results
```
{{% /alert %}}

## Mermaid Diagrams

[Examples of diagrams available with Mermaid - https://mermaid.js.org/syntax/examples.html](https://mermaid.js.org/syntax/examples.html)

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
sequenceDiagram
    participant Client
    participant AP
    participant Gateway
    Client->>AP: Associate
    AP->>Gateway: Authenticate
    Gateway->>AP: Attributes
    AP->>Client: 4 Way
```

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'darkMode': false,
      'background': '#fff',
      'fontFamily': 'Open Source Pro, arial',
      'textColor': '#000',
      'primaryColor': '#ff8300',
      'primaryBorderColor': '#ff8300',
      'primaryTextColor': '#fff',
      'secondaryColor': '#01A982',
      'tertiaryColor': '#7FF9E2',
      'noteBkgColor': '#f6f6f6',
      'noteTextColor': '#000'
    }
  }
}%%
sequenceDiagram
    participant Client
    participant AP
    participant RADIUS Server
    participant Captive Portal
    participant Web Server

    Client->>Web Server: HTTP/HTTPS - Give me page
    AP->>Client: HTTP/HTTPS - The page you are<br />looking for is at<br />https://captiveportal.dom.tld/path/page
    Client->>Captive Portal: HTTPS - give me page https://captiveportal.dom.tld/path/page
    Captive Portal->>Client: HTTPS - here is page https://captiveportal.dom.tld/path/page
    loop Captive portal process
      Client->>Captive Portal: HTTPS - providing information
    end
    Captive Portal->>Client: HTTPS - Post your credentials to the AP
    Client->>AP: HTTPS - Here are my credentials
    AP->>RADIUS Server: RADIUS - Check these credentials
    loop AuthZ/AuthN
      RADIUS Server->>RADIUS Server: AuthN/AuthZ
    end
    RADIUS Server->>AP: RADIUS - ACCEPT or REJECT
    loop Change User Role
      AP->>AP: Assign client role based on result
    end
    Note over Client,Web Server: Assuming correctly authenticated and proper role assigned
    Client->>Web Server: HTTP/HTTPS - Give me page
    Web Server->>Client: HTTP/HTTPS - Here is page
```

## Collapsed Section

The following uses the [`<details>`](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections) tag to create a collapsed section.

<details markdown="block">
<summary>Shopping list (click me!)</summary>

This is content inside a `<details>` dropdown.

- [ ] Apples

- [ ] Oranges

- [ ] Milk

</details>

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
<details markdown="block">
<summary>Shopping list (click me!)</summary>

This is content inside a `<details>` dropdown.

- [ ] Apples

- [ ] Oranges

- [ ] Milk

</details>
{{< /card >}}

## Code Blocks

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

{{< card code=true header="Example markdown source for above" lang="go-html-template" >}}
```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```
{{< /card >}}

### More code

```python
def dump_args(func):
    "This decorator dumps out the arguments passed to a function before calling it"
    argnames = func.func_code.co_varnames[:func.func_code.co_argcount]
    fname = func.func_name
    def echo_func(*args,**kwargs):
        print fname, ":", ', '.join(
            '%s=%r' % entry
            for entry in zip(argnames,args) + kwargs.items())
        return func(*args, **kwargs)
    return echo_func

@dump_args
def f1(a,b,c):
    print a + b + c

f1(1, 2, 3)

def precondition(precondition, use_conditions=DEFAULT_ON):
    return conditions(precondition, None, use_conditions)

def postcondition(postcondition, use_conditions=DEFAULT_ON):
    return conditions(None, postcondition, use_conditions)

class conditions(object):
    __slots__ = ('__precondition', '__postcondition')

    def __init__(self, pre, post, use_conditions=DEFAULT_ON):
        if not use_conditions:
            pre, post = None, None

        self.__precondition  = pre
        self.__postcondition = post
```

```Text
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

An example of `inline code or CLI formatting` within a paragraph, requires using the ` character to open and close the block.
