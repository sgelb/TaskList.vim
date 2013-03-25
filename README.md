TaskList.vim
============

# History

This plugin's origin is from [this script](http://www.vim.org/scripts/script.php?script_id=2607).
It's an awesome tool, but it hasn't been updated in a while. People have been 
adding some nifty functions like more keywords for recognition and what-not, 
but they haven't been centralized. This is my attempt to do so.

I don't know if the original maintainer of this plug-in is still *maintaining*
it, but I'll hold responbility in terms of bug fixes, feature updates and 
releases for this specific repository.

# About

This version of **TaskList.vim** includes the changes of (Pete Lewis's 
fork)[https://github.com/petelewis/TaskList.vim] and (azizlight


# Installation
I recommend using [Vundle](https://github.com/gmarik/vundle#readme).

**Vundle installation:**
```viml
Bundle 'jalcine/TaskList.vim'
```

You're done.

# TODO:
**TaskList.vim** has a lot of potential to improve functionality.

 * allow for variable-defined list of extra keywords for recognition.
 * provide a custom format string for the tasklist buffer.
 * define a unique filetype for the tasklist buffer.
 * allow for loading tasks in all open buffers
 * data sources for tasks (Traq, Bugzilla, GitHub Issues).
 * highlight lines with task keywords in source code.
 * multi-line support for tags.

