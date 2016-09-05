+++
image = "/images/fork-in-railroad.jpg"
date = "2016-09-05T08:54:29-04:00"
draft = false
title = "Is React Native Right for your Business?"
tldr = "React Native allows developers to share code between Android and iOS devices, thereby reducing development time. While React Native can reduce development costs, using the tool is riskier than native mobile development and some features that are available in the newest versions of iOS and Android may not be available through React Native."
+++

## Introduction

If you decide that your business needs a mobile app in spite of [the warning I've given](http://catch22.tech/post/your-business-probably-shouldnt-build-a-mobile-app/), you should consider using [React Native](https://facebook.github.io/react-native/) for your project. React Native is a new tool for cross-platform mobile development. The tool allows developers to share code between Android and iOS devices, thereby reducing development time. While React Native can reduce development costs, using the tool is riskier than native mobile development and some features that are available in the newest versions of iOS and Android may not be available through React Native. This report discusses these tradeoffs in detail.

## Lower-development Costs

Because React Native allows developers to share much of the code between the two platforms, there can be significant development cost savings. [Facebook has reported](https://code.facebook.com/posts/1189117404435352/react-native-for-android-how-we-built-the-first-cross-platform-react-native-app/) that they’ve been able to share up to 85% of their code across Android and iOS in one of their smaller applications. Some have even suggested that the code reuse between the two platforms could be even higher than this.<sup>1</sup>

## Risk

### Worrisome

React Native is not maintained by Apple or Google. Because of this, there's a risk that support for the tool may eventually be dropped. As the following Google Trends graph suggests, Phonegap, a similar cross-platform application development tool that is not supported by Google and Apple may be on its way to this fate.

![downward trend](/images/phonegap-trend.png)

React Native is also a risky proposition because it uses Javascript, a language and ecosystem that is known for being a particularly volatile.<sup>2</sup>

### Promising

React Native is partially a response to the failures of Phonegap as a mobile application development tool.<sup>3</sup> As the name implies, React Native actually allows developers to use native views in their applications. Phonegap, on the other hand, only allowed developers to use webviews, views that don’t look and feel like the views we’ve come to know and love in all of our favorite applications. It’s promising that React Native has recognized the shortcomings of Phonegap as a tool. Hopefully, this recognition will save React Native from becoming irrelevant, a fate that Phonegap may not be able to escape.

React Native is maintained by Facebook. They've invested heavily in the project, and they appear to be happy with the results. As I’ve said before, they’ve reported that they’ve been able to share up to 85% of their code across Android and iOS. They are using React Native in some of Facebook’s apps, including the main Facebook app.<sup>4</sup> This suggests that they will continue investing in and maintaining the project.

## Features

Because React Native is a 3rd-party tool that’s not developed by Google and Apple, there may be some delay between when a feature is released for the new versions of iOS and Android and when that feature becomes available in React Native. If it’s critical that your application be on the cutting edge of new features that are available on mobile devices, React Native may not be a good fit.

## Want to know more?

If you'd like to talk more about whether React Native is a good fit for your development project, check us out at Catch22, an application development company. Checkout our landing page and [leave us your email ](http://catch22.tech/#download) so we can setup a meeting.

## Notes:

1. Adam Miskiewicz at Chalk and Chisle, a development agency that’s done work with the Discovery Channel and Nike is an example of someone who thinks that 85% is not even the upper-bound on the potential for code reused.

1. [There’s a Medium article](https://medium.com/@ericclemmons/javascript-fatigue-48d4011b6fc4#.z5q5db7m1) that pretty well captures this sentiment. Interestingly, the article also suggests that 2016 will be the year that the javascript ecosystem starts to stabilize.

1. [In the blog post announcing React Native](https://code.facebook.com/posts/1014532261909640/react-native-bringing-modern-web-techniques-to-mobile/), Facebook says this about Phonegap-like development tools: "What we really want is the user experience of the native mobile platforms...There are a few ways we can probably achieve this...One possibility is to use WebViews inside simple native wrapper applications. We tried this a few years back...Unfortunately, because all the rendering is done using web tech, we can't produce a truly native user experience."

1. See [the react native showcase](https://facebook.github.io/react-native/showcase.html) for a list of apps that use react native.