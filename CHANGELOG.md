## 0.1.0 - Not released yet

### Improvements

- [#474][] Improve message when access denied. ([@chadcf][])
- [#468][] Launch a repairDatabase in MongoDB database after launching
  the clear_resolved task. ([@shingara][])
- Update gem of Mongoid to 2.7.1
- Update gem of Mongo to 1.8.5
- [#457][] Add task information about db:seed in Readme. ([@mildavw][])
- Add support of Ruby 2.0.0
- [#475][] Return a HTTP 422 status code when you try push notice with
  bad api key. ([@shingara][])
- Return a 400 http status when you try put a notice without args.
  ([@shingara][])

### Bug fixes

- [#469][] Fix issue about the documentation of new heroku addons usage.
  ([@adamjt][])
- [#455][] Avoid raising exception if you comment an exception and no
  other user are define to received this comment. ([@alvarobp][])
- [#453][] Fix ruby 2.0.0 incompatibilities with gem ([@SamSaffron][])
- [#476][] Fix javascript notifier issue with IE8 ([@sdepold][])
- [#466][] Fix not see problem if octokit gem not define ([@tamaloa][])
- [#460][] Fix issue when you try see user with gravatar activate but no
  email define to this user ([@ivanyv][])

<!--- The following link definition list is generated by PimpMyChangelog --->
[#453]: https://github.com/errbit/errbit/issues/453
[#455]: https://github.com/errbit/errbit/issues/455
[#457]: https://github.com/errbit/errbit/issues/457
[#460]: https://github.com/errbit/errbit/issues/460
[#466]: https://github.com/errbit/errbit/issues/466
[#468]: https://github.com/errbit/errbit/issues/468
[#469]: https://github.com/errbit/errbit/issues/469
[#474]: https://github.com/errbit/errbit/issues/474
[#475]: https://github.com/errbit/errbit/issues/475
[#476]: https://github.com/errbit/errbit/issues/476
[@SamSaffron]: https://github.com/SamSaffron
[@adamjt]: https://github.com/adamjt
[@alvarobp]: https://github.com/alvarobp
[@chadcf]: https://github.com/chadcf
[@mildavw]: https://github.com/mildavw
[@sdepold]: https://github.com/sdepold
[@shingara]: https://github.com/shingara
[@tamaloa]: https://github.com/tamaloa
[@ivanyv]: https://github.com/ivanyv
