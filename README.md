# Readme

 Written by: Son Van (in case you need to know who to blame)

### What is this?
  This is the code to create the SIAM CMU student chapter website. To make this work, you need to have the program Jekyll to generate the HTML files for this.

  Why do we use Jekyll? It doesn't require one to have knowledge in HTML/web design to make a good looking/professional website. I've customized it so you can type math equations freely. All you need to know is markdown, which is even easier than TeX. If you've done some blogging before, you know what I'm talking about.

  More detailed information could be found here:
   https://jekyllrb.com/docs/home/.

### Important files
  The most important file is the `_config.yml`. Jekyll will use it to understand where our website is and create relative links accordingly. I'll write about this more when time permits. In the mean time, if you're curious, you could use the link above.

  That said, of course, I've configured the code so it works well with the address provided by the department.
### Write and Build
**Assuming you already clone the directory from github on the machine.**

Writing:
  0) Before writing, you should update the directory from git by go to SIAM-CMU directory (or whatever the first directory is) and type in

    git pull

  1) There are several ways to do this. But the basic step is that you need Jekyll. You can either install Jekyll in your machine or use it in our computer lab **qwe7**.

      (I've requested Joe Evans to install the software and it happens to be on this machine. You can ask him to install it in your office's machine as well.)

  2) To write a post in the ''Upcoming event'' session, create an `.md` or `.markdown` file in the `_post` directory. There's a sample file in there already. The format should be

    YEAR-MONTH-DAY-title.md

  My intention for this session is to post abstracts of talks/events/announcements.

  For more information about writing posts, please see: https://jekyllrb.com/docs/posts/.

Building:
  1) After finishing writing posts, you go to the SIAM-CMU directory (or whatever the first directory is) and type in

    jekyll build

You can see a demo locally on your machine by running the following

    jekyll serve

  2) Commit your changes to github. If you don't know how, go to the first directory and simply follow the following step by step:

    git add --update
    git commit -m "[comments]"
    git push
### Publish
scopy everything in the directory `_site` to directory `public` on our hosting machine. You should get in touch with Son Van for information regarding login to the host.
