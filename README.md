This is a port of Javascript [Showdown] which in turn is a port of [Markdown].

It currently is a direct port, so there are few optimizations or lanuguage specific features in it. It is, however, working fine with the demo on the Showdown site.

In the future it's going to get cleaned up and optimized for Actionscript. I've also implmented it as a static utility type implementation, which is fine right now, and useful in most purposes. However I'm planning to change this so that it becomes more flexible and can become part of a larger tool.

Issues so far:

 * Nested lists don't seem to be working.
 

  [Showdown]: http://attacklab.net/showdown/
  [Markdown]: http://daringfireball.net/projects/markdown/
  