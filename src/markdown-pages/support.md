---
path: "/support"
title: "Support"
authors: gdams, karianna, sxa, tellison, SueChaplain, sxa555, mvitz, ParkerM, M-Davies, Malax, lasombra, practicalli-john, jeffalder, hendrikebbers, douph1, andrew-m-leonard
---

## Community Support

Read [Java Is Still Free (3.0.0)](https://medium.com/@javachampions/java-is-still-free-3-0-0-ocrt-2021-bca75c88d23b) for some background information about Java support options. We are prepared to stand behind our release quality binaries, so each build that is identified as a release receives support via the Adoptium community. Our support means that you can raise an issue to describe a bug you have found in the build, and we will work with you and the appropriate development team to resolve it. Any fixes we identify will be delivered as part of the next Adoptium release.

As a community of open source developers, our commitment is to triage any issues raised and champion them in the appropriate source code project. Of course, if the problem arises from the way we build and test the code we can fix that directly. For higher levels of assurance you should contact commercial companies offering support.

## Release Roadmap

The frequency of Adoptium releases is guided by the schedule of our dependencies.

OpenJDK provide a new feature release every six months, and a maintenance/security update based upon each active release every three months. The release dates for those from the OpenJDK project are the [Tuesdays closest to the 17th](https://www.oracle.com/security-alerts/) of January, April, July and October. We will follow this schedule for publishing binary releases from Adoptium to ensure you get the latest, most secure builds.

In addition, every three years one feature release will be designated as a Long Term Supported (LTS) release. We will produce LTS releases for at least four years. This assurance will allow you to stay on a well-defined code stream, and give you time to migrate to the next, new, stable, LTS release when it becomes available.

Based upon this roadmap, and starting with Java 8 (currently supported releases in bold) here is the timetable for the various releases. Note that specific release dates in here are the ones from the OpenJDK source project and may not match when the Adoptium project will have binaries available - there will usually be a delay while we complete our extensive build and tests cycles.

|First Availability|Latest Release|Next Release|End of Availability <sup>[1]</sup>|
|--- |--- |--- |--- |
|Java 8 (LTS) - Mar 2014 | jdk8u312-b07 - 19th Oct 2021 | jdk8u322 - 18th Jan 2021 | At Least May 2026 <sup>[1]</sup>|
|Java 11 (LTS) - Sep 2018 | jdk-11.0.13+8 - 19th Oct 2021 | jdk-11.0.14 - 18th Jan 2021 | At Least Oct 2024 <sup>[1]</sup>|
|Java 16 - Mar 2021 | jdk-16.0.2+7 - 20th Jul 2021 | EOL | Sep 2021|
|Java 17 (LTS) - Sep 2021 | jdk-17.0.1+12 - 19th Oct 2021 | jdk-17.0.2 - 18th Jan 2021 | TBC <sup>[1]</sup>|
|Java 18 - Mar 2022 |N/A | jdk-18 - 15th Marc 2022 | Sep 2022|

<sup>[1]</sup> As a general philosophy, Adoptium will continue to build binaries for LTS releases as long as the corresponding upstream source is actively maintained.