# Documentation as Code - A first conversion
This is a simple example of how to use documentation as code.

Technologies involved:

* [arc42](https://arc42.org/) to get the structure for the software architecture documentation
* [AsciiDoc](https://asciidoc.org/) as format to write the software architecture documentation
* [Asciidoctor](https://docs.asciidoctor.org/asciidoctor) to generate the representations of the software architecture documentation written in asciidoc 

## Prerequisites

* Install [Asciidoctor](https://docs.asciidoctor.org/asciidoctor), [Asciidoctor PDF](https://docs.asciidoctor.org/pdf-converter/latest/)
    * [Asciidoctor](https://docs.asciidoctor.org/asciidoctor/latest/install/)
   latest/)
    * [Asciidoctor-PDF](https://docs.asciidoctor.org/pdf-converter/latest/install/)

## Generate the software architecture documentation representations


**Generate the documentation as HTML representation**

``
asciidoctor -b html5 my-example-document.adoc
``

**Generate the documentation as PDF representation**

``
asciidoctor -b pdf -r asciidoctor-pdf  my-example-document.adoc
``
