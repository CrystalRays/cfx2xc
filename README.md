最近想把一个Windows下的鼠标主题用在Linux下，于是找到了这个项目，但是年久失修，于是就fork一下，做了点小改动
Recently，I want to use a windows cursor theme in my linux, so I find this project. But it had been out of update for years, 
so I forked it, and did only a few fixes.
=============================Followings is the original author's words 下面是原作者的话======================================

CursorFX is a popular cursor software for Windows, owned by Stardock.

There are many cursor themes available at http://www.wincustomize.com/explore/cursorfx

This script can convert a CursorFX theme to an X11 cursor theme.

 **Do NOT distribute the converted themes without the permission of the original author!** 

Requirement: Python, Python Imaging Library, xcursorgen, tar

Features:
  * Extract the images, convert them into X11 cursor format. Animations are supported
  * Map the CursorFX cursors into X11 cursors
  * Create a tarball for installation
  * support pressed cursors
  * support loop & alternate animation

What're NOT supported so far:

  * repeat/end repeat statements in scripts
  * effects & trails

patches, suggestions are welcome.
