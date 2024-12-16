---
title: "Getting Started with MiniBlog"
date: 2024-12-17
author: "MiniBlog Team"
excerpt: "Learn how to create your first blog entry and use this template effectively."
tags: ["guide", "tutorial", "getting-started"]
---

# Getting Started with MiniBlog

Welcome to MiniBlog! This guide will walk you through the steps to create a new blog entry and familiarize yourself with the template structure.

---

### Step 1: Clone the Repository

You should already have finished this step if you are here. If not, then you should navigate to the repository and press "Use this Template" in the top right. Press create a new repository and name it!

Or, you can clone it using git.
```sh
git clone https://github.com/matfat55/miniblog.git
``` 

<br>

### Step 2: Create a new page!

Navigate to the folder src/content/blog. Inside you should see hello-world.md (this file) and garden.md. This blog works by using markdown files. Your markdown file's names should be descriptive and reflect the content of your post.

<br>

### Step 3: Structure Your Blog Post

Each blog post should start with a frontmatter section at the top, enclosed by three dashes (---). Here's the required format:

```markdown
---
title: "Your Blog Post Title"
date: YYYY-MM-DD
author: "Your Name"
excerpt: "A brief summary of your post"
tags: ["tag1", "tag2", "tag3"]
---
```
The only optional category is the tags. 
<br>
This can be changed by modifying the src/content/config.ts file. 
<br>
<br>

### Step 4: Write Your Content

After the frontmatter, you can write your blog post content using standard Markdown syntax.


I won't teach you markdown here, there are many great resources. If you want to add images, make sure to put them in the public directory. 

### Step 5: Preview Your Blog
Once you've created your post, you can preview it locally by:

Running npm run dev in your terminal
Opening your browser to localhost:3000
Navigating to your new blog post

Step 6: Deploy Your Changes
After you're satisfied with your post:

Commit your changes to git
Push to your repository
Your blog will automatically update if you have deployment set up
Remember to:

Use descriptive titles and excerpts
Add relevant tags to help readers find your content
Include high-quality images when relevant
Proofread your content before publishing
Now you're ready to start blogging with MiniBlog! Happy writing! 🚀