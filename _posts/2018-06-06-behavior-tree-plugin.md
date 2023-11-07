---
id: 1590
title: 'Behavior Tree plugin for Unity'
date: '2018-06-06T07:10:34+00:00'
author: admin
layout: post
guid: 'http://ynotgames.org/ynotwp/?p=1590'
permalink: /behavior-tree-plugin/
post_grid_post_settings:
    - 'a:3:{s:11:"current_tab";s:7:"options";s:19:"custom_thumb_source";s:99:"http://ynotgames.org/ynotwp/wp-content/plugins/post-grid/assets/frontend/css/images/placeholder.png";s:16:"thumb_custom_url";s:0:"";}'
image: /wp-content/uploads/2018/06/bTreePostIcon-1024x621.png
categories:
    - Featured
    - Github
    - Projects
---

A plugin for Unity that facilitates the development of artificial intelligence for games. It features a powerful editor extension that allows the creation of behavior trees through visual scripting, by dragging and dropping nodes and linking them together. It’s easy to extend for each game’s specifics needs and quite performant since each behavior tree can have its own refresh rate, which can run at much lower frequencies than the main game loop.

It also features a blackboard, where shared variables can be defined and their values queried and modified during runtime, enabling communication between nodes, resulting in self-contained and reusable nodes that can create complex behaviors for your actors.

The editor displays nodes in execution, their progress and also uses color coding to make it easier to debug the tree. It’s also possible to manually edit blackboard variables values to force specific branches of your tree and see how it would behave in hard-to-replicate contexts.

Check the video for an example of the plugin in action.

<div class="embed-container"><iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" frameborder="0" src="https://www.youtube.com/embed/MKFnXMPvsbg?feature=oembed" title="Behaviour Tree Plugin" height="450" width="600"></iframe></div>## Version 2

Working every now and then on porting the plugin to the new retained UI mode, UI Toolkit (UI Elements), and GraphNode which has been quite an enjoyable experience so far!

![](/assets/img/wp-content/uploads/2021/01/Btree-GraphNodepng.png)