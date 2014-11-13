vimperator-labs
===============


Vimperator is a Firefox browser extension with strong inspiration from the Vim text editor, with a mind towards faster and more efficient browsing. It has similar key bindings and you could call it a modal web browser, as key bindings differ according to which mode you are in. For example, it has a special Hint mode, where you can follow links easily with the keyboard only. Also most functionality is available as commands, typing :back will go back within the current page history, just like hitting the back button in the toolbar.

However, Vimperator does not try to be a 100% Vim clone, it rather brings Vim's ideas to the 21st century. This means making use of new graphical capabilities but also of faster computers. Furthermore, great care is taken into making its command line interface more consistent and easier to use, while still being a powerful extension for advanced users. 

##### Features

* Vim-like key bindings (h, j, k, l, gg, G, 0, $, ZZ, <C-f>, etc.)
* Ex commands (:quit, :open www.foo.com, ...) with a proper command line
* Tab completion available for all commands, showing suggestions while you type
* Hint mode (start with f to follow a link)
* Extensions! Yes, you can extend Vimperator's functionality with scripts just like you can extend Firefox with extensions
* Explore JavaScript objects with :echo window and even context-sensitive tab completion
* Easily customizable GUI (easily hide all GUI elements with :set gui=)
* Ability to :source JavaScript files, and to use a ~/.vimperatorrc file with syntax highlighting if you install vimperator.vim
* Easy quick searches (:open foo will search for "foo" in google, :open ebay terminator will search for "terminator" on eBay) with support for Firefox keyword bookmarks and search engines
* Count supported for many commands (3<C-o> will go back 3 pages)
* Beep on errors
* Marks support (ma to set mark 'a' on a webpage, 'a to go there).
* QuickMarks support (quickly go to previously marked web pages with go{a-zA-Z0-9}).
* :map and :command support (and feedkeys() for script writers).
* :time support for profiling
* Move the text cursor and select text with Vim keys and a visual mode
* External editor support
* Macros to replay key strokes
* AutoCommands to execute action on certain events
* A comprehensive :help system, explaining all commands, mappings and options
* Much more...
