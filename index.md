## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/sujoyb2/DM-project/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes
   <script>
      async function getUsers() {
        let response = await fetch(
          "http://ec2-3-87-43-244.compute-1.amazonaws.com/countme/abcd"
        );
        let data = await response.json();
        console.log("sujoy")
        console.log(data)
        return data;
      }
      getUsers().then(data => console.log(data));
    </script>

<button class="button button1" onclick="getUsers()">Green</button>
    
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sujoyb2/DM-project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
