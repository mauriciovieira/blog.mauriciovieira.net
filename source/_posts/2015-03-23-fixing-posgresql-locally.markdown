---
layout: post
title: "Fixing posgresql locally"
date: 2015-03-23 22:58:03 -0300
comments: true
categories: 
---
Source: http://stackoverflow.com/questions/25970132/pg-tblspc-missing-after-installation-of-os-x-yosemite

Commands: 
```
 mkdir -p /usr/local/var/postgres/{pg_tblspc,pg_twophase,pg_stat_tmp}/
touch /usr/local/var/postgres/{pg_tblspc,pg_twophase,pg_stat_tmp}/.keep
```
