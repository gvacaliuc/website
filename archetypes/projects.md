+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
type = "project"
description = "{{ replace .Name "-" " " | title }}"
image = "img/projects/{{ .Name }}.png"
draft = true
+++
