Setting up your linter in Sublime Text makes in-line debugging possible and can make your coding experience much less frustrating.

Here is the basic process for making that possible.

First, check to see if SublimeLinter has been installed.
From your menu:
  • Click >> Sublime Text >> Preferences >> Package Settings
  • If SublimeLinter has been installed, it will be in the dropdown

  If SublimeLinter is not present, go ahead and install that from your Package Control (Command + Shift + P)
    • Type 'Install' and select 'Install Package'
    • From there, select SublimeLinter

Once your SublimeLinter has been installed, you are now ready to install your linter plugins for whatever language you want. To install those plugins, go back in to your Package Install Manager (Command + Shift + P):
    • Type 'Install' and select 'Install Package'
    • From there, select your SublimeLinter plugin.

      Examples:
        SublimeLinter-jshint
        SublimeLinter-ruby
        SublimeLinter-rubocop
        SublimeLinter-coffee
        SublimeLinter-php
        etc.

Each plugin will provide documentation for proper implementation, and some installation from the Terminal might be required for plugins such as rubocop or jshint. Further instructions will be in the GitHub page for the plugin.

After you install your plugin, quit and restart Sublime Text!

Your linter settings can be changed via your Preferences >> Package Settings >> SublimeLinter >> Settings-user setting, where you can disable them as needed.

You can also do that from the Sublime Text UI by going in to your Package Control and select 'SublimeLinter: disable linter' - You'll be able to select each individual plugin as needed.

Linter display settings can be personalized by right-clicking on the gutter (where your line numbers are on the left) and selecting the SublimeLinter pulldown.


