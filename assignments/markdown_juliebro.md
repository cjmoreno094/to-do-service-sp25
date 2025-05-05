# Pros and cons of using Markdown as a documentation source language

*By Julie Brodeur*

## To-do list

Things to do in this document:

- [x] Add pros.
- [x] Add cons.
- [x] Format the pros and cons text into a table.
- [ ] Leave one task list item unchecked.

## Pros & cons

Markdown is often used for documentation in docs-as-code workflows. Here's a sample of its pros and cons:

| PROS | CONS |
| -------- | -------- |
| You only need a plain text editor to format in Markdown | Markdown isn't as easy to use as a writing tool with a simple user interface. You need to learn its syntax. There are also different varieties of Markdown with slightly different syntax. |
| Markdown creates text files that are very small compared to the files you create in some writing tools like Microsoft Word. | It can be hard for the team to visualize what the finished documentation product will look like, instead of a collection of text files. In addition, you might need to create a document map to track how different Markdown files are organized together. |
| Because Markdown has few formatting options, you can remember its syntax. | Markdown doesn't have the complex syntax to handle advanced formatting needs like styles. You'll need to develop a style guide to keep formatting consistent across projects. |
| Because the formatting is simple, you can focus on the writing instead of elaborate formatting. | The writing might be more developer-focused because the entire team doesn't have access to the version control system. [^1]|
| Many developers are familiar with this type of formatting, making it easy to share a document with you and contribute to it. | If you allow developers or other team members to change the files directly, you'll need a diff tool to see their changes. There's no "track changes" feature unless you use version control. |
| Markdown's plain text format works well with version control systems like Git. | Many content management systems for traditional documentation are easier and more intuitive to use. |
| Because it's written in plain text, Markdown code is relatively easy to read. | Tables in Markdown are hard to read if you wrap lines of text. If you don't wrap lines of text, then you need to scroll to the right to read the entire line. |
| You can leverage included or add-on utilities to convert Markdown documents to popular web publishing formats like HTML, XML, PDF, and others. | You'll need to integrate one or more utilities or have developers write scripts to convert Markdown to web publishing formats like HTML. |

[^1]: People like tech marketing, product managers, and technical account managers typically don't work within a version control system.

## Other things to consider

- **Different writing platforms have their pros and cons too:** Word is relatively easy to use and share with a team (but the devs can waste time trying to format things and proofread them); Google docs is limited and munges Word files; DITA is a bit difficult to learn as well; large companies can have overwrought tech pubs processes that make it hard to keep up with dev deadlines.
- **Docs-as-code:** If you're including docs with the API or software, the incomplete docs might be a problem for the deadline, or features you don't want announced could be leaked.
- **GitLab article:** Having everyone together in one tool makes everything "transparent and inclusive." Could be good, could be bad!

