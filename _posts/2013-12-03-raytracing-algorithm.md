---
id: 893
title: 'Raytracing algorithm'
date: '2013-12-03T04:28:48+00:00'
author: admin
layout: post
guid: '/docs/ynotwp/?p=893'
permalink: /raytracing-algorithm/
image: /wp-content/uploads/2013/12/raytracing-1.png
categories:
    - Misc
format: image
---

The image above is the rendered output of a raytracing program developed during my M.Sc. The algorithm comprehends two types of shapes, sphere and axis aligned bounding box (AABB) and the following optical effects:

- diffuse reflection
- specular reflection
- ambient reflection
- ambient light
- multiple point lights shadow

The program was developed using C++, OpenGL and freeglut.