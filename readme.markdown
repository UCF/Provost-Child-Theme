# Provost WordPress Theme

WordPress child theme for the Office of the Provost.  Extends [UCF WordPress Theme](https://github.com/UCF/UCF-WordPress-Theme).


## Installation Requirements

This theme is developed and tested against WordPress 4.7.3+ and PHP 5.4.x+.

### Parent Theme
**UCF WordPress Theme** must be installed on your WordPress instance for this theme to function properly.

### Required Plugins
Any plugins required by UCF WordPress Theme must be installed for this theme to function properly.


## Configuration
Make sure you've followed all of the [UCF WordPress Theme configuration instructions](https://github.com/UCF/UCF-WordPress-Theme#configuration).

This theme has no other unique configuration steps.


## Development

Note that any compiled, minified css and js files are included within the repo.  Changes to these files should be tracked via git (so that users installing the theme using traditional installation methods will have a working theme out-of-the-box.)

[Enabling debug mode](https://codex.wordpress.org/Debugging_in_WordPress) in your `wp-config.php` file is recommended during development to help catch warnings and bugs.

### Instructions
1. Clone the Provost-Theme repo into your development environment, within your WordPress installation's `themes/` directory: `git clone https://github.com/UCF/Provost-Theme.git`
2. If you haven't already done so, create a new WordPress site on your development environment, install the required plugins listed above, and then set the Provost Theme as the active theme.
3. Make sure you've done all the steps listed under "Configuration" above.
