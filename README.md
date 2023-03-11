# Planning for an updated Frida documentation

_Planning how to make the Frida documentation better_

This document examines the current state of the Frida documentation and discusses how to make it better.

## Current state of the documentation and support

### Current availability of documentation

1. [Official Frida documentation (frida.re/docs)](https://frida.re/docs/)  TODO: Describe what's currently in the documentation.
1. [Learn Frida and Frida Handbook](https://learnfrida.info/), by [Fernando Diaz](https://learnfrida.info/about_faq/).
The site has online documentation (HTML) and the book is accessible liberally from the same site and also the NowSecure Academy site.
1. _Other locations?_

### User support 

1. Users can get [Frida support on Telegram](https://frida.re/contact/). There are currently 2720 members. _Frida OffTopic_ has 457 members.
1. Users can get [Frida support on IRC/Freenode #frida](https://frida.re/contact/). Less than ten people on the channel, probably inactive due to the split between Freenode and Libera.
1. There is a #frida channel on Libera Chat. There were 13 users on that channel when I visited. The existence of the channel is not listed on the frida.re website yet.
1. [Github Issues on github/frida/frida](https://github.com/frida/frida/issues). The Github Issues are (ab)used as a help venue.

## Rationale (for the update of the Frida documentation)

Every free/open-source project should make known and understood what it does. This enhances the viability and may bring more contributors to the project.

The most difficult part of maintaining a project is the software development aspect. The documentation and the growing of the community are easier and should not be neglected.

## Types of audience for this documentation

The documentation should cater the following groups of users

1. Power users that are experienced with other computer-related tasks and want to expand to Frida.
   The documentation should relate to their prior knowledge when explaining Frida. 
1. Users with experience in Frida that want to consult the documentation as a quick reminder for some task.
   The documentation should not be exclusively in screencasts but in text form for easy copy-pasting of complex commands. The commands should be easy to identify. When you select a line, it should not select the Unix prompt.
1. Users with little computer experience but willing to make the effort to learn. 
   They should get a good understanding what Frida does, be able to successfully set up Frida, and perform at least an easy task. 
1. Users are are interested in the applications of Frida but will ask someone else to take up the task/job.
   They should be able to have a good understanding what Frida does and be able to evaluate roughly the difficulty of the task/job.

## Purposes of documentation

* Avoid repeated questions on the support channels.
* Show best practices for common tasks.
* Cover initial successful installation on a variety of operating systems. Include Troubleshooting. Include simple verification tasks that the installation was successful. 
* The documentation should be accessible, by the search engines. The majority of users search on a search engine. Commons searches should direct to the documentation. It will also be picked up by those AI search engines.

## What should go in the new documentation

* Discussion article: What is really Frida? Type of _Access to the address space of a running software_. Use _Cheat Engine_ as example. Cheat Engine does read/write/set on the data segment to alter the number of lives or coins. Newer Cheat Engine [also does code inject, with assembly!](https://wiki.cheatengine.org/index.php?title=Tutorials:Auto_Assembler:Injection_full).
* Discussion article: What is really Frida? Practical explanation with Greasemonkey/Tampermonkey/Violentmonkey. Actually, [Violentmonkey](https://github.com/violentmonkey/violentmonkey), which is the one with active development.
* Installation, general instructions for Windows/Linux/OSX, individual articles for each major OS version, with Troubleshooting section and verification examples that it was installed successfully. The individual articles are there so they can be picked by search engines and used by new users.
* Reference article: What are those different packages in the assets, https://github.com/frida/frida/releases (i.e. _code devkit_, _gum devkit_,...)
* Android: how to setup Frida on a rooted phone
* Android: how to inject the Gadget in the APK, how to get the APK from the phone in the first place.
* _TODO_

## TODO

* Add documentation on https://github.com/frida/frida/issues when you create a new Issue. Instruct how to collect better information for a bug report. Should say that it is not a support venue.
* Use forum software? Perhaps not discord (walled garden, inaccessible by search engines). [Managed like StackExchange](https://area51.stackexchange.com/) or [self-hosted like Discourse](https://github.com/discourse/discourse).
