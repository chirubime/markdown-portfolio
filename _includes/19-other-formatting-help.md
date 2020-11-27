This is for quoting:

> Pardon my French


You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

Certain words and phrases need to be formatted in monospace fonts, especially when writing about code. As you've seen throughout this lab, words can be distinguished in markdown with inline code blocks.

Inline code is just one ``` character on either side of the text, and can be used within paragraphs, headers, or other Markdown.

`inline code is just one backtick`

To separate out a larger block of code, use three ``` characters instead of one, and set the text aside in its own paragraph.

What we type is the extra dashes

```
Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
```

In addition to code blocks, some code blocks should be rendered differently depending on the language, such as Javascript or command-line text.

What we type are the dashes and the sh

  ```sh
  github-learning-lab ~/Projects/recipe-repository
  $ git init
  Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
  ```
 Most of the text in this issue is formatted in collapsible summary blocks. Here's how to make them with Markdown:

<details>
  <summary>Summary</summary>

  Secret hi

</details>
