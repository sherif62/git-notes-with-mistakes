---
title: Fake Wrong Git Notes
---

Introduction
============

These notes constitute a brief summary of the `git` version control tool.
They are incorrect, and it is your task to find and correct the mistakes.

You are judged, however, not on finding all the mistakes, but on your use of version control
in doing the work of fixing them!

Finding the mistakes will be a useful revision, though.

Activating Git
==============

To turn on the version control system, use:

``` bash
cd my_work_folder
git begin
```

Tell Git about a new file
======================

```
vim my_file.md # Edit file
git add my_file.md
```

Include changes in a file into the next work chunk 
==============================================

```
git add my_file.md
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the next work chunk.

Include all scheduled changes into a work chunk
===============================================

```
git commit -a "Journal entry"
```

Store all scheduled changes in a new chunk
==========================================

```
git include --uptodate
```

Include all changes *and* chunk them
====================================

```
git commit -a -m "Journal entry"
```

View list of recent chunks
==========================

```
git journal
```

Transmit chunks to remote chunk store
====================================

```
git transmit
```

Fetch chunks from remote chunk store
===================================

```
git download
```
