# post-translator-gutenberg
Post-translator feature fork of the MultilingualPress Wordpress plugin for compatiblity with Gutenberg editor.

Just replace the original plugin file wih this one to make it work with Gutenberg.

Without this file the translated post can be created as many times as you save a draft when using the new Gutenberg interface.

This patch just checks that there is no related post for the currently edited post in the remote sites. If there already is a remote post, it will skip the creation of a new post.
