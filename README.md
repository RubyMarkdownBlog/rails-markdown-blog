# Enjoy blogging with "Markdown" and "Git". An open source personal blog engine based on Ruby on Rails 8.

## How can I write articles locally with Markdown files and publish them with `git push`? 

At present, [Jekyll](https://jekyllrb.com/) or [Hugo](https://gohugo.io/) can already meet the above requirements, not perfectly.

**RailsMarkdownBlog** can also meet the above requirements, yet it is different in a few ways.

## Why do I need **RailsMarkdownBlog**?

1. The blog posts generated by Jekyll or Hugo are *static*, while *RailsMarkdownBlog* is a **dynamic** blog engine.
    - The functions of *static* blogs are very limited.
    - In *dynamic* blog *RailsMarkdownBlog*, email subscriptions are currently integrated, and in the future, portfolios, comments, likes, reading counts, online payments, etc. will also be supported.
    - Also, you can **add some customized features** to your blog.
    - You might say, what if I don't know how to program in Ruby?
        - Two years ago, this would be a problem, but now, we have AI, and you can **let AI help you implement some small functions**!
        - If there is an error, tell AI and let AI correct it.
2. For those who are not familiar with Jekyll or Hugo, it is even **difficult** to even find a good-looking theme.
    - *RailsMarkdownBlog* currently supports one **beautiful free theme**, and more themes will be added in the future.
3. Their documentation is a lot of pages long. Who can explain everything in just one page?
    - *RailsMarkdownBlog* can. For information on how to write a blog using Markdown and Git, read [markdown-blog](https://github.com/RubyMarkdownBlog/markdown-blog) using the *RailsMarkdownBlog* approach.

## Why don’t developers blog much anymore?

- After using [GitHub Pages](https://pages.github.com/) (based on Jekyll), they **rarely** write blogs. Why?
- IMO, ordinary blog systems can **no longer create much value for bloggers**! Those blogs are not designed to bring value to bloggers.
- Take myself as an example, my GitHub Pages' [Lane's old blog](https://gazeldx.github.io/) is not sexy at all, so I can't get excited about writing.

## RailsMarkdownBlog: A blog engine focused on bringing value to developers

- You can see [Lane's new blog](https://lane.blog5.com) (based on *RailsMarkdownBlog*) is well-designed.
- I started expecting clients to **pay for my services directly on my blog**!
- Through the blog, I convey a message to potential customers: I am an expert in web development, algorithms, and game addiction!

# Installation of RailsMarkdownBlog

## TODO: not finished

## Free theme 'DevBlog' installation

### Download 'DevBlog' Theme

- Option 1: Use Git to download.

    If your network is not good, you can try `option 2`.

    ```shell
    cd _themes
    git clone https://github.com/xriley/DevBlog-Theme.git
    ```

- Option 2: Download zip file and unzip it to `./_themes` folder.
    1. The zip file is at:
        - GitHub: [DevBlog-Theme zip](https://github.com/xriley/DevBlog-Theme/archive/refs/heads/master.zip)
        - Or official website: [DevBlog Theme](https://themes.3rdwavemedia.com/bootstrap-templates/personal/devblog-free-bootstrap-5-blog-template-for-developers/).
    2. Copy `DevBlog-Theme-master.zip` into `./_themes`.
    3. Run `cd ./_themes && unzip DevBlog-Theme-master.zip`.
    4. Run `mv DevBlog-Theme-master DevBlog-Theme` to rename it.

### Install 'DevBlog' Theme

Run:

```shell
cd ./_themes # if not in this folder
sh install-theme-devblog.sh
```

## Run tests

Run `bundle exec rspec spec`.
