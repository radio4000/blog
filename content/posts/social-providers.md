---
title: "Removing sign-up (then logins), with social providers Google and Facebook"
date: 2020-12-02
slug: removing-social-providers-google-facebook-login
---

> In an effort to free the project from dependencies, the creation of
> a new user (therefore a radio), will no longer be possible, using
> any external social providers. Also, in a close future we will
> enforce login with email/password for every users that are currently
> using social providers.


Currently Facebook and Goole have been provided as a matter of
convenience for user who might not wish to create for themeselves an
account using an email/password pair.

This "feature" is being rolled out for several reseaons:

- bugs and annoyance in managing API keys for OAUTH applications (the
  Facebook and Google app and keys used to authenticate into
  radio400), and Firebase projects keys (issue with functions deployment).
- wish to become independent from Google's Firebase, have a portable
  (hopefully one day decentralized) infrastructure
  
Instead, users will be able to:

- create a new user and radio with email/password
- update their current login method to email/password

We're sorry for the inconvenience, please get in touch (find info on
feedback or contact page on the site) if your encounter any troubles.


See issue for public discussion: [github/radio4000/issues/482](https://github.com/internet4000/radio4000/issues/482)
