---
title: How to create Laravel Project with Composer (docker)
date: 2022-09-07 15:35:00 Z
published: false
categories:
- software engineer
tags:
- docker
- php
- laravel
- composer
---

with docker installed just run this command in the parent folder of project
---


    docker run --rm --interactive --tty \
      --volume $PWD:/app \
      composer create-project laravel/laravel project-name
