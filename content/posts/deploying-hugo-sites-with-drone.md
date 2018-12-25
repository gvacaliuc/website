+++
title = "Deploying Hugo Sites With Drone"
date = "2018-12-24T21:27:37-05:00"
type = "post"
description = "use drone to deploy hugo sites to github pages"
image = "img/posts/drone-logo.svg"
github = "gvacaliuc/website"
draft = false
tags = ["hugo", "drone", "github-pages"]
+++

This is using the new `1.0.0` drone file syntax.  This uses username / password
authentication to push, so you're required to set the `gh_password` secret on
the drone repo.  

{{< gist gvacaliuc 68eb1a8c8f8f03cea0056c0a8da23bf5 >}}
