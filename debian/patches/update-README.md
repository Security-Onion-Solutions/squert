Description: <short summary of the patch>
 TODO: Put a short summary on the line above and replace this paragraph
 with a longer explanation of this change. Complete the meta-information
 with other relevant fields (see below for details). To make it easier, the
 information below has been extracted from the changelog. Adjust it or drop
 it.
 .
 securityonion-squert (20161212-1ubuntu1securityonion10) trusty; urgency=medium
 .
   * Squert: error when removing comment #1066
Author: Doug Burks <doug.burks@gmail.com>

---
The information above should follow the Patch Tagging Guidelines, please
checkout http://dep.debian.net/deps/dep3/ to learn about the format. Here
are templates for supplementary fields that you might want to add:

Origin: <vendor|upstream|other>, <url of original patch>
Bug: <url in upstream bugtracker>
Bug-Debian: http://bugs.debian.org/<bugnumber>
Bug-Ubuntu: https://launchpad.net/bugs/<bugnumber>
Forwarded: <no|not-needed|url proving that it has been forwarded>
Reviewed-By: <name and email of someone who approved the patch>
Last-Update: <YYYY-MM-DD>

--- securityonion-squert-20161212.orig/README.md
+++ securityonion-squert-20161212/README.md
@@ -4,6 +4,6 @@
 
 SQueRT is a tool that is used to query event data.
 
-NOTE: Squert was originally developed by [Paul Halliday](http://www.pintumbler.org/words/youcantgobackonlyforward).
+NOTE: SQueRT was originally developed by [Paul Halliday](http://www.pintumbler.org/words/youcantgobackonlyforward).
 Thanks to Paul for all of his hard work over the years!
 This is a fork of Paul's latest version that is maintained by the Security Onion team and includes modifications specific to Security Onion.
