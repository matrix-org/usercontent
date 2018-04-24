UserContent
===========

A way to render user generated content with a different origin to the main application.
This can be used to avoid XSS attacks.

This is used by Riot to display content in end-to-end encrypted chats. See
https://github.com/vector-im/riot-web/blob/master/README.md#configjson for
instructions on how to host your own version of this.

This is not an ideal solution for Riot: see
https://github.com/vector-im/riot-web/issues/6173 for status on replacing
this with something else.
