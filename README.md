#NationBuilder Foundation Theme

# Add This (NationBuilder) Event

**Add This (NationBuilder) Event** is a simple plugin for using the popular [Add This Event][ate] plugin on your [NationBuilder][nationbuilder] event pages. It will allow your supporters to add your events to their preferred calendars from your NationBuilder event pages with a single click.

## Copyright / License

**Add This (NationBuilder) Event** is a simple port of of [Add This Event][ate], and is subject to the same liscensing requirements. For more information, see [addthisevent.com][ate].

## How to use this theme

To use this plugin:

1. Upload all the files contained in this repository to your theme’s directory.
2. Add `{% include "partial_ate_settings" %}` to your `layout.html` file just above the `{{ content_for_footer }}` tag.
3. Add `{% include "partial_add_this_event_link" %}` to your `pages_show_event.html` and `pages_show_event_wide.html` templates where you’d like the “Add to Calendar” link to appear.
4. (Optional) Import the `_add_this_event.scss` file into your `theme.scss` stylesheet in order to customize the styling of the widget as desired.

[ate]: http://addthisevent.com/
[nationbuilder]: http://nationbuilder.com/?recruiter_id=219736