---
layout: post
title: Writing Your First Post
tags: ["introduction"]
---

### Setting up Your First Post

To write your first post on your new website, navigate to the `/_posts/` folder from your repositories main directory. If you forked the repository you will see all of the posts that I wrote in your `_posts` folder, along with the file `2022-01-01-template.md`. You can delete all of the files *except for this template file*, which you will use to quickly make new posts.

To delete files, you simply click on the file to view it, then hit the trash can in the top right corner.

![A screenshot of the top right corner of each GitHub file. It shows a menu of icons, with the last icon, which is circled here in red, being a trash can.](/assets/img/post/first-post-01.png)

Once you have deleted everything except for the template file, open the template file. In the same menu on the top right where you see the trash can, there is an icon that looks like two squares overlapping. This is the 'copy' icon. Click on it to copy the contents of the file.

![A screenshot of the same menu, with the icon that looks like two squares overlapping circled in red.](/assets/img/post/first-post-02.png)

Now return to your `/_posts/` folder and create a new file.

![A screenshot showing the dropdown menu 'Add file > create new file'](/assets/img/post/first-post-03.png)

For now leave your file unnamed and paste the contents of the template file that you copied earlier.

For ease of editing, I always choose the 'soft wrap' option to allow the text to wrap.

![A screenshot showing the drop down menu 'Line wrapmode > soft wrap'](/assets/img/post/first-post-04.png)

### Naming Your Post

You post files must contain the date in YYYY-MM-DD format, representing the date that the post was published, followed by a short titled with all spaces represented by a `-`. 

### Front Matter

The first part of every post will be the **front matter**. This is the information that appears between the sets of `---` dashes.

```
---
layout: post
title: 
tags: ["TAG1", "TAG2", "TAG3"]
published: false
---
```

The `layout` will always be `post`.  
The `title` is where you write the title of the post as you'd like it to appear on your website.  
`tags` is where you can categorize the post. You can create whatever tags you want for your blog, and you can add as many or as few as you would like. Tags should be written as shown here, within brackets and with each tag in quotation marks.  
`published` is followed by `true` or `false` and tells GitHub whether you want the post to appear live on your website or not. If you are drafting a post you may wish to keep it unpublished, or maybe you changed your mind about a post but don't want to delete it completely.

### Writing Your Post

The body of your post can be written in [markdown](https://github.github.com/gfm/) or HTML, or a mix of the two. 

If you are a visual artist, the most important markdown syntax will be how to insert an image. You can upload images into your `/assets/img/` folder and point to them with the following markdown.

```
![Image Description](/assets/img/YOUR-IMAGE-NAME)
```

