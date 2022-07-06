## ORQA Web Automation Demonstration Site

A static page to serve as a broadly accessible demonstration for various automation procedures using IB Boost's ORQA automation platform.

Accessibly publicly at https://ibboost.github.io/orqa-web-demo-site/

### Maintainers

The syntax is Markdown; whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

For more details on features here see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Links

[IB Boost](https://ibboost.com/)

[ORQA](https://orqa.io/)

[w3c.org](https://www.w3.org/standards/xml/transformation) for the basics of XML transformation

### Example Raw XML

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<TABLE style="border-collapse: collapse;" border="0">
<COLGROUP>
<COL width="20.74%" align="left"/>
<COL width="79.26%" align="left"/>
</COLGROUP>
<THEAD>
<TR>
<TH style="border-right: 0.5pt solid ; border-bottom: 0.5pt solid ; " colspan="1" align="left">ColumnA</TH>
<TH style="border-right: 0.5pt solid ; border-bottom: 0.5pt solid ; " colspan="1" align="right">ColumnB</TH>
</TR>
</THEAD>
<TBODY>
<TR>
<TD style="border-right: 0.5pt solid ; border-bottom: 0.5pt solid ; " align="left">Some normal text</TD>
<TD style="border-bottom: 0.5pt solid ; ">
<P>I drive a grey sedan.</P>
</TD>
</TR>
<TR>
<TD style="border-right: 0.5pt solid ; border-bottom: 0.5pt solid ; " align="left">Some freaky text</TD>
<TD style="border-bottom: 0.5pt solid ; ">
<P>!5]q¦ºÎåøĈßŮǼȸʶʬʥ͌ϠδШͽӜѾ֍ᴽאᶿḨ†‽₦₷☻﴾</P>
</TD>
</TR>
</TBODY>
</TABLE>
```

### Example Lists

#### Colours

- Orange
- Blue
- Purple
- Turquoise 
- Ultramarine

#### Notable things about carrots

1. Edible
1. Grow underground
1. Originally purple
1. Favourite of rabbits
1. Often mistaken for dynamite in cartoons
1. Used for snowman rhinoplasty

### Example Tables

#### Simple Table

Col1 | Col2
---- | ----
First 1 | First 2
Second 1 | Second 2

#### Complex Table

ID | Date | Item | Quantity | Price 
---- | ---- | ---- | ---- | ----
12345 | 20/03/1986 | E.T. Sunglasses | 6 | 3.99
76543 | 19/12/1980 | Luke Skywalker Sarong | 2 | 15.88
55555 | 4/9/1998 | Pikachu Electric Heating Hat | 1 | 60
9816 | 5/5/2005 | Bender Head Polish | 19 | 21.21


#### Unicode Character Table

Who | Favourite saying
--- | ---
Bart | "Don't have a cow"
Michaelangelo | "Cowabunga"
Alien Bob | "!5]q¦ºÎåøĈßŮǼȸʶʬʥ͌ϠδШͽӜѾ֍ᴽאᶿḨ†‽₦₷☻﴾"
Powdered Toast Man | "Powdered Toast Man!"

### Other Webpage Features

#### Task List

- [x] Download ORQA
- [x] Automate all the things
- [x] Be amazed
- [ ] Go to sleep

### Meta-programming snippets

#### JavaScript

**Go back a page**

```javascript
window.history.go(-1)'
```

**Create a fancy alert**

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

Updated 20220706
