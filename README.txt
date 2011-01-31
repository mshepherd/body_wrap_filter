Body Wrap Filter Module
=======================

Body wrap filter is a small theme-helper module which provides an input filter
to wrap the contents of the node's body field in a div.

Sometimes, when I'm working with custom content types that may have many
additional fields besides the title and body content, it can be tricky to style
the content that was added to the body field. It can be done using a theme
template (.tpl.php) and writing each field separately, but this can be tedious
when a simple div wrapper around the body field would suffice.

An input filter seems like a neat way to do this.

Requirements
------------

There are no special requirements for this module, only that you follow the
installation and configuration notes below.

Installation
------------

Follow the normal procedure to install a module.

See http://drupal.org/node/70151 for further information.

Configuration
-------------

To get this filter working for any of your site's input formats:

1 Navigate to the input formats admin page - admin/settings/filters/list
2 Click the configure link next to the desired input forma
3 Select the checkbox next to 'Wrap body field content'
4 Check if the HTML filter is selected (*)
5 Save the configuration

(*) If you are also using the HTML filter, you should change the weight of this
filter so that it is triggered after the HTML filter. Open the Rearrange tab to
make this change.
