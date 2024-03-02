This exists as a lightweight demo of some of the more useful markdown features.

Table of contents:
- [h1](#heading-1)
- [h2](#heading-2)
- ...

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

- some
- nested
    - list
    - of
        1. items
        1. wololo
- end

---

1. some
1. nested
    1. numbered
    1. list
        - of
        - items
1. paragraph-insert below
    
    ***tab this paragraph to not break numbering***

1. note how numbers are continuous
1. end
---

*italic text*

**bold text**

***bold-italic text***

~~strikeout~~

sub<sub>script</sub>

super<sup>script</script>

<font size="+3" style="color:red">styled text</font>

> Block quote. ***You can mix this with other markdown.***
> - like lists
> - `and code `
>
> It supports multiple paragraphs.
>> and nesting

    tab

        double tab

---

`code here` this one is inline

This one is for a code block. Don't forget to specify language type.

```c#
public class Calculator
{
    // This method adds two integers and returns the result
    public int Add(int num1, int num2)
    {
        return num1 + num2;
    }
}
```

---

Link to [heading](#heading-1).

Link to image (put images into `media` folder):

![alternative text](/media/orange.png)

Link to image on the web (supports GIFs too):

![alternative text](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages.alphacoders.com%2F500%2F500310.jpg&f=1&nofb=1&ipt=0198feec5bd19108ce366ff0241ce2544781cf9bd9353130deea72aaca856e7d&ipo=images)

> Images can be sized.

Link to [website (markdown rules)](https://www.markdownguide.org/).

Verbatim links automatically get covered:

- https://www.markdownguide.org
- some.email@domain.com

---

| Feature | Description | Example |
|:--|:--:|--:|
| **Bold**          | **Bold text** for emphasis                   | `**bold**`         |
| _Italic_          | _Italic text_ for emphasis                   | `_italic_`         |
| `Code`            | Use backticks for `code` formatting          | `` `code` ``       |
| Hyperlinks        | [Title](URL) for links                       | `[Google](https://google.com)` |

Notes:
- For alignment, `:--` aligns left, `--:` aligns right, and `:--:` centers the text in the column.
- Markdown does not support row or column span.