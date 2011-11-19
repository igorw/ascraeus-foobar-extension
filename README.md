# Foobar Extension

This is an extension for the development version of phpBB 3.1. It's the first ever released phpBB extension.

## What it does

The foobar extension solves a very unique problem. Do you sometimes wake up at night and wish you had a "foobar.txt" file with a localized version of the text "Foo Bar", followed by the second count of the minute that the file was created? And don't you also want this file to update every time a user on your board visits any page?

Enter the foobar extension! It does precisely that, to show off, without being useful in any way, how phpBB extensions can add cron tasks and language files easily.

## Installation

Just place the extension into `ext/foobar` and enable it.

There is no UI for enabling extensions yet, so you will have to:

    INSERT INTO phpbb_ext (ext_name, ext_active) VALUES ('foobar', 1);

But that's really it! That's all you have to do!

Oh, and make sure foobar.txt in your board root is writable.

## License

GPLv2 of course, just as phpBB3.
