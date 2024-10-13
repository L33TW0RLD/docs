---
Title: 'Images'
Description: 'Embedding an image is very similar to adding a link in Markdown: markdown Alt text  - Add an exclamation mark ! - Followed by the alt text in square brackets [Alt text] - And the path or URL to the image asset in parentheses ( ).'
Subjects:
  - 'Developer Tools'
  - 'Web Development'
Tags:
  - 'Images'
  - 'URL'
  - 'Documentation'
  - 'GitHub'
CatalogContent:
  - 'learn-html'
  - 'paths/front-end-engineer-career-path'
---

Embedding an image is very similar to adding a link in Markdown:

```md
![Alt text](URL or file path)
```

- Add an exclamation mark `!`
- Followed by the alt text in square brackets `[Alt text]`
- And the path or URL to the image asset in parentheses `(` `)`.

For example:

```md
![Sonny and Mariel high fiving.](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif)
```

The output would be:

![Sonny and Mariel high fiving.](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif)

An optional title can also be added after the URL, still in the parentheses:

```md
![Sonny and Mariel high fiving.](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif 'High Five')
```

## Linked Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

This technique is useful when you want the image to also function as a link, directing users to another page when they click on it.

```markdown
[![HTML Image Example](https://raw.githubusercontent.com/Codecademy/docs/main/media/html-image-example.png "HTML Image Example")](https://www.codecademy.com)
```

The output would be:

[![HTML Image Example](https://raw.githubusercontent.com/Codecademy/docs/main/media/html-image-example.png "HTML Image Example")](https://www.codecademy.com)S