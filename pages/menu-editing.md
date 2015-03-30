# Editing the menu

Menus are optional; not all themes will necessarily use a menu, and you
don't have to fill it in if you don't want to. Having said that, if you
do, you'll need to know what to do.

## The file format

Open the `content-demo/menu.txt` file and compare what you can see to
the menu that's visible (on the right hand side of this page) in the
browser.

You'll notice that each line in the file refers to the path to one of
the files in the `pages` directory, with the file extension removed.
You'll also notice that a menu item can have nested menu items beneath
it, and that each sub level is indented by two spaces.

Here's another example, fleshed out a bit to represent a more typical
site. The first line represents the site's home page.

    /
    blog
    docs
      marking-up-pages
        examples/using-markdown
        examples/using-textile
        examples/using-haml
        adding-attachments
      menu-editing
      publishing-a-feed
    support
      faq
      knowledge-base
    about
    signup

## What gets displayed?

The entire menu doesn't necessarily have to be displayed on the page at
once. Nesta has helper methods that you can use to display parts of the
menu tree, so you can easily build primary and secondary navigation from
one `menu.txt` file.

This probably isn't the right place for us to get into the details; see
the [menu documentation][menu-docs] for more.

[menu-docs]: http://nestacms.com/docs/creating-content/menus
