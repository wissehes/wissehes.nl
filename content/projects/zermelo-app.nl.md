---
title: "Zermelo App"
date: 2022-09-19T09:40:45+02:00
draft: false
---

<!-- ## Zermelo App -->

Our school system (zermelo) didn't have an app (only a sluggish web app). So I wanted to see if I could make a proper iOS app for it. I first looked for any documentation on their API, which thankfully existed (unlike with magister...). I saw that their api is very simple to work with.

After that, I first tried fetching and showing the schedule in a [simple react app](https://github.com/wissehes/zermelo-react-app). After finding out that their authentication method was requesting an access token by providing the Zermelo api with a code that shows up in the Zermelo dashboard, I was very surprised, I expected them to require me creating an application in some developer dashboard.
