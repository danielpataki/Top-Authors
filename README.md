# Top Authors

A highly customizable widget that allows you to display the top authors of your website easily.

## Description

Top authors allows yoy to list your top authors with plenty of options. You can set the following in each widget:

- Widget title
- Roles to exclude
- Post types to include
- Authors to show
- 4 Preset display templates
- Custom display template that allows you to create a completely custom structure and modify the output before and after the list.
- Archive (category/tag/taxonomy) specific author lists

For a more detailed description of how you can set up custom author lists take a look at the other notes section. The plugin also has some developer friendly features, take a look at the other notes section for more.

#### Thanks

-[Seb Van Dijk](https://twitter.com/sebvandijk) for donating this plugin to me for free, I owe you one :)
-[Font Awesome](http://fortawesome.github.io/Font-Awesome/) for the plugin icon

#### Translations

The plugin is currently available in English and Hungarian. Please feel free to submit any new languages via a pull request, I'd be mighty thankful.

#### Useful Links

This Github repository is for the development of this plugin. If you would like to read installation and in-depth usage instructions you might want to look at the WordPress plugin page instead.

- [Plugin Page](https://wordpress.org/plugins/top-authors/)
- [SVN Repository](http://plugins.svn.wordpress.org/top-authors/)

# Developer Features

Currently there are two filters you can use to control the options available in the widget.

- `ta/usable_roles` allows you to change the roles that can be selected. It should return an array of roles in the form of slug=>name
- `ta/usable_opst_types` allows you to change the post_types that can be selected. It should return an array of post type objects
- `ta/post_query` allows you to modify the arguments of the WP_Query which retrieves the posts that we look up the authors for. Modify the arguments if you want to force category-specific top authors on single post pages, or other similar uses


# Want To Help?

If you like the plugin and you like helping others out there are a few things you can do:

- **[Review the plugin](https://wordpress.org/support/view/plugin-reviews/top-authors)**
- **Submit a translation** If you speak another language goodly, you can submit a language file, I'd be mighty thankful! Take a look at the lang directory to see what languages we already have. If a language isn't there create one and submit a pull request. If you have no idea what I'm talking about drop me a line and I'll help you out
- **[Tip me on Gratipay](https://gratipay.com/danielpataki/)**
