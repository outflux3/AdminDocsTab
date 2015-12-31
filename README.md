AdminDocsTab module for ProcessWire
================

Admin helper to add help tab and optional docs page in [ProcessWire CMS](http://processwire.com/).

### Processwire helper modules for managing documentation

## Instructions

This is a helper module which expects you to have already setup a hidden part of your page tree to establish your documentation, using any template (e.g. 'docs') and a body field (ckeditor).

The docs template does not need to have an output template, as the module will only echo the body field inside the admin.

In addition this 'docs' template will require a template select field (separate module) which should be named template_select.

Once you have setup your docs template, template_select field and some docs pages, you should install the AdminDocsTab module, then select the template(s) to show the docs on, as well as the root page of your docs.

At this point the 'Docs' tab should show up for the relevant template (as specified in the Doc), and show the docs that have that template specified.

To have a global docs overview page, which renders all of the docs in an accordion view, you can install the ProcessDocsView module, which will setup a page to view the docs, under setup.


## Example Docs Tab

![Desc](https://raw.githubusercontent.com/outflux3/AdminDocsTab/master/images/admin_docs.jpg)

 