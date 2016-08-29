+++
date = "2016-08-27T21:32:22-04:00"
draft = true
title = "Your Business Probably Shouldn't Build a Mobile App"
image = "/images/intro.png"
tldr = "Mobile apps are sexy, but they're not cheap, and the golden age of apps is over. Only build a mobile application if your software needs access to mobile-only sensors (e.g., accelerometer), mobile-specific UI gestures (e.g., swipe, pinch to zoom), or has complicated offline data storage needs. Otherwise, consider building a responsive (mobile-friendly) web application instead."
+++

## Sexy, but not cheap

Mobile apps are sexy. Whenever I tell people that I develop mobile applications, their eyes light up. They ask me what apps I've been working on and they often pitch me on a "million dollar idea" for an app. Planet of the Apps, a new reality TV show about mobile application development, is further evidence that people are fascinated with mobile applications and the businesses that are built around them.

Its easy to get caught up in the app hype. Huge companies like Facebook, Uber, and Airbnb may make us think that building a mobile app can result in huge benefits for our businesses. While this is true in some cases, the reality is that building a mobile application for your business can be a big waste of time and money.

We can start to see how expensive mobile applications are if we look at the average salary of a mobile application developer. According to X, the average yearly salary is X, which leads to an hourly rate of about Y. With just one week of full-time work, your mobile app already has a price tag of Z. If you want to build your application for both Android and iOS, you *may* need to double that price tag because the code that works for Android won't work for iOS.<sup>1</sup>

Now, these salary surveys are just that: surveys of people who are working at companies with a salary. If you hire a freelance developer, however, you may find that the hourly rate they charge is much higher than the rate you see for salaried employees. The reason for this is that freelance developers need to cover the cost of their own insurance and other benefits (like vacation time) that are already included in the compensation package of salaried employees. I've heard experienced freelance developers advise new freelancers to charge twice the hourly rate they would have if they were regular salaried employees, and I've known developers who have charged $200/hr for their services.

Even large companies like Google and Facebook are sensitive to the development costs of mobile applications. Both companies have created tools that allow them to share code between iOS and Android phones.<sup>2</sup> If these large companies are worried about development costs, you and your small business should be worried too.

## The Golden Age is Over

KPCB, an venture capital firm that invests in internet startups, has published a report that points out that the growth of mobile devices is decelerating and that the money spent in Apple and Google's app stores has been shrinking for the past 3 years.


X also reports that most mobile phone users are downloading 0 apps per month. Presumably, this fact was the central motivation for Google to release its new "Instant App" feature for Android this past summer, a feature that allows users to run an Android application without downloading it.<sup>3</sup> It may be sexy to talk and think about mobile apps, but for many mobile phone users, apps aren't sexy enough to even download let alone pay for.

## Do you really need an app?

So, mobile apps are expensive and people today are less willing to download and spend money on them. Does that mean your business can't benefit from a mobile application? Not necessarily. The point here is just that it's worth considering whether there's a better way to solve your business' problem.

In many cases, developing a responsive web application may be a better choice for your business. Responsive web apps don't require separate code for Android and iOS and with the advent of web application frameworks with angular and react, it can be cheaper and faster to develop a web application instead of a native mobile app. Moreover, web applications offer many of the same benefits native mobile apps have.

The Google I/O conference app is a nice case-in-point here. Below are some videos of the Android app and the responsive web app for Google I/O, a yearly developer conference.

Can you tell the difference? Probably not. So, a web app can, in some cases, deliver many of the same benefits as a native mobile app without the big price tag. Because of this, I recommend that you only build a mobile application if your app needs

1. mobile-specific UI gestures like "swipe" and "pinch to zoom"
1. complicated offline data storage
1. access to the mobile device's sensors

There might be some other cases where it does make sense to build a mobile app instead of a web app, but I think the this list covers the most common cases.

If you're pretty tech-savy, you may have some objections to this recommendation. You might ask, "But what about push notifications?" Turns out web apps can do that.<sup>4</sup> Then you might ask, "What about offline access?" Web apps can do that. In fact, the video that you saw above on the left demonstrates a web application that allows offline access. Finally, you might ask, "But what if I need the user's location data?" Web apps can do that too.

## Conclusion

If you're considering building an app for your business, don't get caught up in the app hype. Consider whether a responsive web application may better suite your needs. Even if you decide a mobile app is right for you, if price is an issue for your business, consider hiring us at Tango. We're a new kind of software development company that works with pre-professional software engineers to develop awesome apps at an awesome price. Check out our landing page for more info.

If you know a small business owner that's looking to build a mobile app and you think this article will help them, please share it and save them some money!

### Notes:

1. You may not need to double this price tag if you're using a cross-platform application development tool like React Native.

1. These tools are called "java2Objc" and "React Native," respectively.

1. I suspect that Apple will copy this feature by next summer.

1. Don't believe me? Visit facebook.com through your mobile browser and you'll be prompted to allow push notifications.