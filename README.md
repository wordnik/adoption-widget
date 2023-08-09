# adoption-widget
a widget for word adoptees to use to advertise their love of their adopted word (and Wordnik)

## spec

### purpose

The adoption widget should allow a word-adopted to add a banner to their blog or site that:

* shows the word they've adopted
* links to that word on Wordnik

The widget should be: 

* easy to create
* easy to install

### user flow: 

* user enters adopted word
* widget checks Wordnik adoption DB
* widget populates "adopted by" field with adopter's name
* (if user is logged in) widget links adopter's name to Wordnik user page
* widget creates link to adopted word
* widget saves HTML of widget for user to copy/paste

### design

Widget should:

* be a standard IAB banner size
* include the Wordnik logo
* include text about the adoption, with links "[USERNAME] has adopted the word [WORD] at Wordnik!"

### process

* create sample designs : widget, widget creation page
* create sample HTML/CSS
* Javascript prototype
* finalize design, HTML/CSS
* merge page into main site
