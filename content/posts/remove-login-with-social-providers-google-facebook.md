---
title: "Removing sign-up (then logins), with social providers Google and Facebook"
date: 2020-12-29
slug: removing-social-provider-login-with-google-facebook
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

- wish to become independent from Google and Facebook
- start first steps to become independent from Google's Firebase, used
  as database and API provider for this project
- bugs and annoyance in managing API keys for OAUTH applications (the
  Facebook and Google app and keys used to authenticate into
  radio4000)
- bugs in Firebase projects keys ([service account issue, with functions deployment](https://stackoverflow.com/questions/62754227/firebase-hosting-deploy-with-serviceaccount-fails-with-403))
  
Instead, users will be able to:

- [create a new user and radio channel with email/password](https://radio4000.com/auth/login)
- [update their current user's (channel) login method to email/password](https://radio4000.com/settings/account)

We're sorry for the inconvenience, please get in touch by any mean if your encounter any troubles or have any feedback:

- project issue for public discussion: [github/radio4000/issues/482](https://github.com/internet4000/radio4000/issues/482)
- [radio4000/feedback](https://radio4000.com/feedback)
- [radio4000/contact](https://radio4000.com/about/contact)
