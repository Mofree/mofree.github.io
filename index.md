## Try GitHub Pages
### How I made this page
- Well, I just followed the instructions below:  
[Getting Started with GitHub Pages](https://guides.github.com/features/pages/): Step by step to have a initial github pages.  
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/): 
Now you can edit your .md file in your repository by using markdown to change your page's content.  
[Working with GitHub Pages](https://docs.github.com/en/github/working-with-github-pages): More instructions from GitHub Docs.  
[GitHub Pages](https://pages.github.com): GitHub Pages official website.  

- Before I moved on, I had some trouble with Markdown about how to generate a line break.  
[Line breaks in markdown](https://gist.github.com/shaunlebron/746476e6e7a4d698b373): Personal repository about line breaks in github Markdown.  
(My own habit: two space for line break; two space + enter for new paragraph; enter if a sentence is too long)  

- I got my homepage now, but how can I make more pages for my website?  
[Creating new files](https://docs.github.com/en/github/managing-files-in-a-repository/creating-new-files): 
Add a new file in my repository. Open it by the link https://*username*.github.io/*filename.md* (more information see below)  

- After I created a new .md file, I found it wasn't shown in my chosen Jekyll theme.  
[Setting up a GitHub Pages site with Jekyll](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll): Github docs about Jekyll.  
[Adding content to your GitHub Pages site using Jekyll](https://docs.github.com/en/github/working-with-github-pages/adding-content-to-your-github-pages-site-using-jekyll): More presisely, I knew from this url that the main types of content for Jekyll sites are pages and posts.  
[Pages](https://jekyllrb.com/docs/pages/): "Pages" in the Jekyll documentation.  
If I open a .md file by the link https://*username*.github.io/*filename.html* then the content will shown in my chosen Jekyll theme. Also, after that I found https://*username*.github.io/*filename* can achieve the same effect. The example is about pages, not posts.  

- So, how about posts?  
[Posts](https://jekyllrb.com/docs/posts/): "Posts" in the Jekyll documentation.  
I summarize a few points:  
  - All blog post files must begin with front matter.  
  - Jekyll uses the Liquid templating language to process templates.  
  - Some predefined global variables can be set in the front matter of a page or post, while some can only be set for a post. (If I understood it correctly)   
  - Ways to include images, downloads.  
  - Ways to create an index of posts on another page.  
  - Jekyll has first class support for tags and categories in blog posts.  
  - You can access a snippet of a posts’s content by using excerpt variable on a post.  

- After a brief reading, I start to test the post function  
  - I created a file under the folder '_posts', and the file's name should be like *YYYY-MM-DD-NAME-OF-POST.md* as instructions says.  
  - I added YAML frontmatter at top of the file.  
  - [Github Pages + jekyll 全面介绍极简搭建个人网站和博客](https://zhuanlan.zhihu.com/p/51240503): I admit that I find this instruction easy to understand.
  - I followed the instruction above and created a blog_list.html file to show the brief information of my posts.  
  - [This is the blog_list.html](https://mofree.github.io/blog_list.html)  
  - Still some problems to be resloved...  

- problems:  
  - 上面的 blog_list 的链接里为什么没有内容？  
  - Liquid表达只能在.html中写吗？不可以在.md文件中写吗？  
  - 缩略显示post部分内容的功能如何实现？

--------------------------------------------------------------------------  
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/mofree/mofree.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mofree/mofree.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
