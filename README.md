FLOSS Best Practices for Bots & Tools
=====================================

Any project that is valuable for an on-wiki workflow really must have certain things to protect the community. Developers put in a lot of effort to build new things and keep them running. No one should feel that they must be available 24/7/365 to support their applications. On the other hand, the sun never sets on the Wikimedia movement and useful and popular projects will experience issues at all times of the day and night. By adopting a few simple practices, a tool maintainer can make it easier for others to help them out and keep their tool running.


Pick a license
--------------
Without a clear license you are implicitly claiming copyright without providing an explanation of the rights you are willing to grant to others who wish to use or modify your software. This means that you retain all rights to your source code and that no one may reproduce, distribute, or create derivative works until standard copyright lapses. In the US today that means until 70 years after your death. This is counter to the general principles of the Wikimedia movement and a violation of the Toolforge terms of use.

Need help choosing a license? Visit https://choosealicense.com/ for a guide to various FLOSS licenses.


Publish the code
----------------
The Wikimedia movement is all about open knowledge. Publishing your source code has numerous potential benefits and very few downsides. It is fairly trivial to setup a git repository with public browsing and downloading capabilities. The Wikimedia Foundation, BitBucket and GitHub all provide this as a gratis service. The Wikimedia Foundation hosting is also libre if that is important to you. As a bonus, you get a backup of your code that lives somewhere besides Toolforge and/or your laptop.


Have co-maintainers
-------------------
Everybody needs a day off now and then. Sometimes we even need a long wiki break to recharge. Having multiple maintainers makes doing that easier without putting a burden on your users or the Toolforge admins. A co-maintainer doesn't have to be a highly technical person either. At the bare minimum you just need someone who can restart things when they are down and shout for help when restarting doesn't make things better.

Don't forget to update your contact documentation to let others know who to poke when they have issues!


Write some docs
---------------
Write just enough documentation so that every maintainer can help with restarts and basic troubleshooting. Where? A wiki page is always ready for you in the Tool namespace on Wikitech, but really anywhere is fine. Add a MAINTAINERS file to your git repo, make a subpage in your User namespace on Wikitech or your home wiki; put it wherever you like, but put it somewhere.


Going beyond
------------
Use a version control system to track how your code changes over time and make it easier to figure out if you are running the same version of the code when debugging. • Make a public bug tracker (and check it for bug reports). • Put your maintenance documentation on Wikitech in the Tool namespace so it's easy to find. • Put some end user end-user documentation on your favorite wiki and link to it from your tool itself if it has a web interface and/or the Tool namespace page for your tool. • Build your tool using other Wikimedia and 3rd-party FLOSS projects (API client libraries, application frameworks) to save time and make it a bit more likely that others can contribute. • Make a new tool for each unrelated activity. Tool accounts are cheap and basically disposable. It will be easier to attract co-maintainers and to eventually hand your tool off to someone else if you lose interest if there is one thing that the tool does.


Credits
-------
"intellectual property" by Arthur Shlain from the Noun Project. CC BY 3.0
"Source Code" by Creative Stall from the Noun Project. CC BY 3.0
"people" by TukTuk Design from the Noun Project. CC BY 3.0
"Write" by Simon Keating from the Noun Project. CC0
"spaceship" by Tatyana Kyul from the Noun Project. CC BY 3.0
"Wikimedia Foundation logo - horizontal.svg" by Wikimedia Foundation. CC BY-SA
3.0
"CC BY-SA" by Creative Commons. CC BY 4.0

Copyright © 2017, Bryan Davis & Wikimedia Foundation. Licensed under the
Creative Commons Attribution-ShareAlike 4.0 International Public License.
