---
layout: page
title: "Download Ruby"
lang: en
---

Here you can get the latest Ruby distributions in your favorite flavor.
The current stable version is {{ site.downloads.stable.version }}.
Please be sure to read [Ruby’s License][license].
{: .summary}

### Ways of Installing Ruby

We have several tools on each major platform to install Ruby:

* On Linux/UNIX, you can use the package management system of your
  distribution or third-party tools (rbenv and RVM).
* On OS X machines, you can use third-party tools (rbenv and RVM).
* On Windows machines, you can use RubyInstaller.

See the [Installation][installation] page for details on using
package management systems or third-party tools.

Of course, you can also install Ruby from source on all major platforms.

### Compiling Ruby — Source Code

Installing from the source code is a great solution for when you are
comfortable enough with your platform and perhaps need specific settings
for your environment. It’s also a good solution in the event that there
are no other premade packages for your platform.

See the [Installation][installation] page for details on building
Ruby from source. If you have an issue compiling Ruby, consider using
one of the third party tools mentioned above. They may help you.

* **Current stable:**
  [Ruby {{ site.downloads.stable.version }}][stable-gz]<br>
  sha256: {{ site.downloads.stable.sha256.gz }}

* **Previous stable:**
  [Ruby {{ site.downloads.previous.version }}][previous-gz]<br>
  sha256: {{ site.downloads.previous.sha256.gz }}

* **Old stable:**
  [Ruby {{ site.downloads.old.version }}][old-gz]<br>
  sha256: {{ site.downloads.old.sha256.gz }}

{% if site.downloads.tooold %}
* **Too old stable (will EOL soon!):**
  [Ruby {{site.downloads.tooold.version}}][tooold-gz]<br>
  sha256: {{ site.downloads.tooold.sha256.gz }}
{% endif %}

* **Snapshots:**
  * [Stable Snapshot][stable-snapshot-gz]:
    This is a tarball of the latest snapshot of the current stable branch.
  * [Nightly Snapshot][nightly-gz]:
    This is a tarball of whatever is in SVN, made nightly.
    This may contain bugs or other issues, use at your own risk!

For information about the Ruby Subversion and Git repositories, see our
[Ruby Core](/en/community/ruby-core/) page.

The Ruby source is available from a worldwide set of
[Mirror Sites][mirrors].
Please try to use a mirror that is near you.



[license]: {{ site.license.url }}
[installation]: /en/documentation/installation/
[stable-gz]: {{ site.downloads.stable.url.gz }}
[previous-gz]: {{ site.downloads.previous.url.gz }}
[old-gz]: {{ site.downloads.old.url.gz }}
[tooold-gz]: {{ site.downloads.tooold.url.gz }}
[stable-snapshot-gz]: {{ site.downloads.stable_snapshot.url.gz }}
[nightly-gz]: {{ site.downloads.nightly_snapshot.url.gz }}
[mirrors]: /en/downloads/mirrors/
