## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/jxie45/Python-Programming/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
  Open Coviar cvs. file
  Change column 
  Change index
  Turn into dataframe from adjancy matrix
  Turn dataframe into graph
  Use networkx to check graph node, edge, statistics information

1. Numbered
   Phase1, Phase2, Phase3, ... Phase1
3. List
   Graph 1, Graph2, Graph3, ... Graph11
   

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
# Code: 

create_using = [nx.DiGraph(G[i]) for i in range(1,12)]
d = [nx.algorithms.link_analysis.hits(create_using[i], max_iter=1000000) for i in range(len(create_using))]
print(d)






For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jxie45/Python-Programming/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
