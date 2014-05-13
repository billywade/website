---
layout: default
title: Download
navgroup: download
---

# Download

The latest Mono release is: **3.2.7**

Please choose your operating system to view the available packages.

<dl id="mono-download" class="tabs vertical" data-tab>
  <dd class="active"><a href="#panel-mac"><i class="fa fa-apple"></i>&nbsp;Mac OS X</a></dd>
  <dd><a href="#panel-lin"><i class="fa fa-linux"></i>&nbsp;Linux</a></dd>
  <dd><a href="#panel-win"><i class="fa fa-windows"></i>&nbsp;Windows</a></dd>
</dl>
<div class="tabs-content vertical">
  <div class="panel content active" id="panel-mac">
    <p>Mono for Mac OS X is available as a Mac Package (.pkg).</p>
    <p>Please refer to the <a href="{{site.github.url}}/docs/install/mac">installation guide</a> for more information about how to install and configure your Mono environment.</p>
    <div>
      <a href="https://github.com/akoeplinger/mono/releases/download/mono-{{page.latestmono}}/Mono_Mac.pkg" class="button radius"><i class="fa fa-download"></i> Download Mono_Mac.pkg</a>
    </div>
  </div>
  <div class="panel content" id="panel-lin">
    <p>Mono for Linux is available as a binary package for the following distributions: Debian/Ubuntu, openSUSE.</p>
    <p>Please refer to the <a href="{{site.github.url}}/docs/install/linux">installation guide</a> for more information about how to install and configure your Mono environment.</p>
    <div>
      <a href="https://github.com/akoeplinger/mono/releases/download/mono-{{page.latestmono}}/Mono-Linux.deb" class="button radius"><i class="fa fa-download"></i> Download Mono-Linux.deb</a>
    </div>
  </div>
  <div class="panel content" id="panel-win">
    <p>Mono for Windows is available as a Windows Installer (.msi) package.</p>
    <p>Please refer to the <a href="{{site.github.url}}/docs/install/windows">installation guide</a> for more information about how to install and configure your Mono environment.</p>
    <div>
      <a href="https://github.com/akoeplinger/mono/releases/download/mono-{{page.latestmono}}/Mono-Windows.msi" class="button radius"><i class="fa fa-download"></i> Download Mono-Windows.msi</a>
    </div>
  </div>
</div>

# Release Notes

This is the Mono 3.2.7 release.
Changelog:

  * much improved ABCREM pass
  * ...
  
<hr/>

The release notes of older Mono versions are available [here]({{site.github.url}}/docs/release-history).
