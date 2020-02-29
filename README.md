Combine Community Contributors
=============================

We adhere to [Moya Contributor Guidelines v1.0.0](https://github.com/Moya/contributors/tree/1.0.0). 
This is mostly an adjusted copy of the [RxSwift Contribution Guidelines](https://github.com/RxSwiftCommunity/contributors).

tl;dr

- Contributors can get added to the organization (with push access) after a single merged pull request. This is still a manual process, so please ask if you'd like to be added.
- No pressure, though! Contributing to open source should never feel like a burden.
- Pull requests are always peer reviewed.
- If it feels right, merge. We can always revert later if we need to.
- We aim for public discussion.

The community also has discussions in Slack, too, so not all info is available in issues. You're welcome to [join the conversation](http://slack.combine.community/).

One important point: CombineCommunity is not affilated with Apple in any way. We're an open-source organization for community-based projects _using_ Combine.

Stewarding a Project
--------------------

If you have a project that you think belongs under the Combine Community organization, please [open an issue](https://github.com/CombineCommunity/contributors/issues/new). Generally, projects should be production-ready and able to be installed with CocoaPods, SPM or Carthage.

### Checklist for Transferring Ownership

When you open an issue, you can copy & paste the following checklist into the description or a comment to track progress:

```
- [ ] replace copyright with "Copyright (c) Combine Community" in code
- [ ] replace copyright in README
- [ ] replace copyright in LICENSE
- [ ] Add `cocoapods@combine.community` as an owner of your project's CocoaPod by using `pod trunk add-owner YourPodName cocoapods@combine.community`.
- [ ] update the remote URL of the Podspec (if any)
- [ ] update CI badge
- [ ] update CI settings
- [ ] transfer repository ownership (once you're a contributor)
- [ ] fork the repo back to your personal account
```

Code of Conduct
---------------

We have our own [Code of Conduct](Code of Conduct.md), which is adapted from the [Contributor Covenant](http://contributor-covenant.org), version 1.3.0, available at [http://contributor-covenant.org/version/1/3/0/](http://contributor-covenant.org/version/1/3/0/). The CoC is taken seriously by the project owners.