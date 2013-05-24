# Frontent tests

Some **tough** tests for assessing the skills of a frontend developer.

## How to use

This is an [XWiki](http://www.xwiki.org/) application, so it requires a running XWiki instance.

To build it, you need [Apache Maven](http://maven.apache.org/). Once `mvn` is available, simply run `mvn clean install` to obtain a *XAR* file in the `target` subdirectory: `target/xwiki-application-frontend-test.xar`

This XAR can then be [imported](http://platform.xwiki.org/xwiki/bin/AdminGuide/ImportExport) in a running XWiki.

## Structure

An index of all the tests is available from the homepage of the `Test` space.

There are several categories of tests:

### CSS tests

All of the tests involve writing CSS code. Each test contains a description of the test, followed by one of the following:

* an image for depicting the expected result
* a link to edit the CSS code
* the HTML source code that needs to be styled
* the actual HTML that will have the edited CSS applied

### JavaScript tests

Most tests involve analyzing one or more snippets of JS code, predicting the outcome of running that code, and explaining why that outcome occurs. Each such test contains:

* a question
* one or more JS snippets

The final two tests involve analyzing a full JS source file, explaining that code, and writing a short snippet that uses those widgets in a meaningful way. These tests contain:

* a link to an external resource
* a task
* a link to edit the JS code
* an eventual HTML code that acts as the target for the JS code

### Velocity tests

These test the ability to work with a very simple, but most probably unknown programming language. They contain an easy task, implementing an algorithm in Velocity. As usual, they contain a link to edit the code, and reloading the document will print the outcome of running the script.

The last test is more complex and involves using XWiki APIs.

### XML tests

Theoretical questions about XML concepts and libraries, XPath and XSLT.

### Logic tests

A few logic tests, plus statistics and probabilities.

### Support tests

These are much easier tests that can be used for candidates for support positions. Domains include Java, CSS, JavaScript, plus general web architecture and support procedures.

### Design tests

A couple of design tasks that should be given as a homework.