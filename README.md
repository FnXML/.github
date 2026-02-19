<img src="fnxml-icon.png" align="left" width="200" style="margin-right: 15px;">

# FnXML

FnXML is a set of Elixir native XML tools

The aim of this project is to provide composable Elixir native tooling for XML and related specs.

These projects are new-ish, so there are some rough edges.

## Available/In Progress

**FnXML** 

| Standard | Version | Status |
|----------|---------|--------|
| [XML 1.0](https://www.w3.org/TR/xml/) (includes DTD) | Fourth & Fifth Edition | Supported |
| DOM API | 1-4 | Supported |
| SAX API | 1.0, 2.0 | Supported |
| StAX API |  | Supported |
| Elixir Streams | | Supported |
| [Namespaces in XML 1.0](https://www.w3.org/TR/xml-names/) | Third Edition | Supported |
| [Canonical XML 1.0](https://www.w3.org/TR/xml-c14n/) | 1.0 | Supported |
| [Exclusive XML Canonicalization 1.0](https://www.w3.org/TR/xml-exc-c14n/) | 1.0 | Supported |
| [XML Signature Syntax and Processing](https://www.w3.org/TR/xmldsig-core1/) | 1.1 | In Development |
| [XML Encryption Syntax and Processing](https://www.w3.org/TR/xmlenc-core1/) | 1.1 | In Development |

**FnXPath**

| Standard | Version | Status |
|----------|---------|--------|
| XPath    | 1.0     | Supported |
|          | 2.0     | Supported |
|          | 3.1     | Supported |

**FnXSD**

| Standard | Version | Status |
|----------|---------|--------|
| XSD      | 1.0 (2nd Ed) | 90% |
|          | 1.1     | In development |

**FnRelaxNG**

|Standard | Version | Status |
|---------|---------|--------|
| Relax NG | 1. 0   | Supported |


**FnSOAP**

| Standard | Version | Status |
|----------|---------|--------|
| SOAP     | 1.2     | Supported |

## Early Stages

Early stage work is being done on an Elixir Native HTML/CSS -> Layout -> SVG/PDF tools.  Which should make generating PDFs from pure Elixir more straight forward.

**FnHTML**

| Standard | Version | Status |
|----------|---------|--------|
| HTML     | 5       | poassing ~65% of html5 conformance tests |

**FnCSS**

| Standard | Version | Status |
|----------|---------|--------|
| CSS      |         | ~20%   |

**FnLayout**

This is a layout engine for FnHTML and FnCSS, which will generate layout input for FnRender.

Early stages, it will render multiple fonts, and uses FnRender to get text dimensions.

**FnRender**

This is a Zig project which provides Pango and Cairo as a port for converting FnHTML -> FnLayout -> [SVG, PDF].

This functions, and likely still needs quite a bit of work.

## Planned

**FnQuery**

**FnXSLT**
