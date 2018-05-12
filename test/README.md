#  Test Page

Note that we use Github-Flavoured [Kramdown].

1.  This should be replaced with a Table of Contents.
{:toc #toc}

This is a paragraph of text.
This is a second line in the paragraph of text.

This is a second paragraph of text.
A horizontal rule follows:

 - - -

This text is **strong**.<br />
This text is *emphasized*.<br />
This text is <dfn>a defining term</dfn>.<br />
This text is <i>offset from the surrounding material</i>.<br />
This text is <b>marked as a key word</b>.<br />
This text is [linked](./).<br />
This text is ~~deleted~~.<br />
This text is <ins>added</ins>.<br />
This text is `code`.

<aside markdown="block">
  This is an aside.
</aside>


 >  This is a blockquote.
 >  This is the second line of the blockquote.

<div role="note" markdown="block">
**Note:**
This is a note.
</div>

<div class="pull" markdown="block">
This is a block of particularly meaningful text.
</div>

+ This is a shortlist
+ It has three items
+ Third item
^
1.  This is a numbered shortlist
2.  Each item is numbered

Term 1
: This is a definition list

Term 2
: Here is another term
: This term has multiple definitions

 +  This is a lengthy list.
    Each item in this list is a paragraph.

 +  Here is a second paragraph for our lengthy list.

^

1.  This is a lengthy numbered list.
    Each item in this list is a paragraph as well.

2.  Here is a second paragraph in our lengthy numbered list.

Term 1

 :  This is a definition list of paragraphs.
    This paragraph has multiple lines.

    Here is a second paragraph.

Term 2

 :  Here is a second paragraph in our definition list.

|  ID  |  Content  |
| :--: | :-------- |
|  01  |  This is a table.  |
|  02  |  This table has multiple items.  |
| ---- | --------- |
|  11  |  A second body in the table.  |
|  12  |  Item 2 of body 2.  |
| ==== | ========= |
|  ID  |  Content  |

##  This is an H2 header {#header-h2}

###  This is an H3 header {#header-h3}

####  This is an H4 header {#header-h4}

#####  This is an H5 header {#header-h5}

######  This is an H6 header {#header-h6}

```xml
<element attribute="value">
	<!--  Comment  -->
	This is some XML code.
</element>
```

```json
{
    "@type": "as:Object",
    "content": "This is a JSON-LD object",
    "number": 123,
    "float": 1.23,
    "exp": 1.0e10,
    "arr": [],
    "nil": null,
}
```

[Kramdown]: <https://kramdown.gettalong.org/syntax.html> "Syntax &#124; kramdown"
