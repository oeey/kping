# kping

Console visual ping history

**Summary:** kping will continually ping a target host.  While the node is offline,
it will report '-'.  When the returns online, it will report '.'.

**Programmed by:** Kenneth Burgener <kenneth@oeey.com> (Sep 2011)

**GitHub:** https://github.com/oeey/kping

**Usage:**

    $ kping [-a:DOWNBELL] [-A:UPBELL] [-r:RESTART] <SERVER>

**Options:**

    -a - UPBELL   - audio bell on ping recovery
    -A - DOWNBELL - audio bell on ping loss
    -r - RESTART  - restart minute count on state change

**Change Log:**
* May 2018 - Github
* Sep 2012 - Initial version
* Oct 2011 - Minute wrap
* Jul 2012 - Added options, audio bell, minute count, restart flag

