EMMET CHEAT SHEET
=================

CORE SYNTAX
-----------
Child:            div>p
Sibling:          h1+p
Multiply:         li*3
Climb Up:         div>ul>li^p
Grouping:         div>(header+footer)

CLASSES & IDS
-------------
ID:               div#app
Class:            div.container
Multiple classes: div.box.red.large
Attributes:       input[type=text]

NUMBERING
---------
Basic:            li.item$*3
Padding:          li.item$$*3
Reverse:          li.item$@-*3

TEXT CONTENT
------------
Text:             p{Hello World}
Numbered text:    li{Item $}*3

HTML STRUCTURES
---------------
Boilerplate:      !
Navbar:           nav>ul>li*5>a
Form:             form>input:text+input:password+button
Table:            table>tr*3>td*4

FORM SHORTCUTS
--------------
input:text
input:email
input:password
input:number
input:checkbox
input:radio
input:file
textarea
button
label

CSS SHORTCUTS
-------------
Margin:           m10
Padding:          p10-20
Width:            w100
Height:           h50
Display flex:     d:flex
Justify center:   jc:center
Align center:     ai:center
Flex direction:   fd:column
Background:       bgc:red
Text color:       c:#fff
Border:           bd1#000

ADVANCED
--------
Lorem:            lorem
Lorem words:      lorem10
Link with text:   a[href="#"]{Click me}

PRACTICE PATTERNS
-----------------
ul>li.item$*5
header>nav>ul>li*4>a
form>input:text+input:email+textarea+button

TIPS
----
- Press TAB to expand Emmet
- Works in VS Code, Sublime, WebStorm
- Combine multiple shortcuts for power
