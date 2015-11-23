---
layout: default
---

# What is aaSemble?

aaSemble helps you deliver more reliable applications and services faster.

The best practices for delivering software have changed quite a bit over the last half dozen years or so. There are various flavors of cloud ([Amazon EC2](https://aws.amazon.com/ec2/), [Heroku](https://www.heroku.com/), [Google Container Engine](https://cloud.google.com/container-engine/), [etc.](https://en.wikipedia.org/wiki/Category:Cloud_platforms)) that can host your application. [Travis-CI](https://travis-ci.org/) helps you test your code. [New Relic](https://newrelic.com/) collects performance metrics. [Sentry](https://getsentry.com/) collects exceptions from your application. [Opbeat](https://opbeat.com/) keeps track of your releases, exceptions, and metrics.

All of these are very useful and they've all made an impact on how we all deliver services to our customers.

Most of these services excel when your application is built from a single source code repository, your deployment pipeline has just a single step ("It builds? Ship it!"), and if everything runs on a single node.

We believe reality is far more complex than that. Most real services consist of many nodes, running a variety of services, built from numerous source code repositories. The tools we use to manage them should reflect that.

We believe enabling better test facilities will mean more reliable services and applications.

We believe deploying your service is the beginning of really learning about it, rather than the end of the development process.

We believe that smaller updates are better than big ones, but also that a thorough test process sometimes takes longer than the time between changes from your code sources, so while per-commit deployments are ideal, they aren't always feasible.

aaSemble is still a very young project. We'll eventually be offering our services on a simple pay-per-use model as well as [making them available](https://github.com/aaSemble/python-aasemble.django/) under the Apache 2.0 license, so you're free to run them on your own infrastructure as well as provide feedback in the form of patches, bug reports, etc.

You can find us on [Github](https://github.com/aaSemble/), [Twitter (@aaSemble)](https://twitter.com/aaSemble), on IRC on Freenode (#aasemble) or even on [Facebook](http://www.facebook.com/aaSemble/).
