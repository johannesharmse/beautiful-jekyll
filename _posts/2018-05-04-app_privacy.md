---
title: Biting the Hand that Feeds
subtitle: Has the end of privacy arrived?
---

It is no secret - smartphones and network connectivity have become the foundation of essentially every human need on the Maslow pyramid. If Syrian refugees are of the opinion that a smartphone is [more important than food](http://www.independent.co.uk/news/world/europe/why-do-refugees-have-smartphones-syrian-woman-explains-perfectly-refugee-crisis-a7025356.html), it would be ignorant of developed country citizens to believe otherwise.

<p align="center">
  <figure align="center">
    <img src="/img/blog/app_privacy/maslow.jpg" width="228" height="228" title="https://www.pacetechnical.com/fast-wifi-basic-human-needs/" style="border: #404040 2px solid;">
    <figcaption> <a href="https://www.pacetechnical.com/fast-wifi-basic-human-needs/">Image</a>: A modern take on Maslow's<br>Hierarchy of Needs.</figcaption>
  </figure>
</p>

Quoting the slam poet, [Watsky](https://genius.com/Watsky-awesome-phone-commercial-lyrics), "it's more than a smartphone, it's a [Mensa](https://en.wikipedia.org/wiki/Mensa_International)". We use smartphones for everything - navigation, socializing, banking, dating, shopping, transportation, research, and everything in between. Mobile app development has shifted from trying to figure out how to satisfy known public's needs, to figuring out what the public's needs are before the public does.

On the surface it appears as if we are living in a modern Utopia, where big companies, such as Google, Facebook, Tinder and Uber are waiting on us hand and foot. However, if we look beneath the surface, a much darker reality gets revealed - a reality where free services come at a price.

We often neglect the fact that every company out there is a business that is modeled in a way that allows for future growth. A company cannot stay afloat if they do not make a profit. Silicon Valley wouldn't be Silicon Valley if those companies weren't generating an income in some way. Indirectly, the users of these services are still paying, even though the service might be advertised as free.

*So how are we paying for these free services? The answer - data.*

The answer seems anti-climactic to say the least. The media has covered this topic time and time again - [companies are using YOUR data for targeted ads](https://lifehacker.com/5994380/how-facebook-uses-your-data-to-target-ads-even-offline). Once people make peace with the fact that their personal data is being collected with the goal of providing them with better ads, they move on with their lives and continue to use these services as before. Receiving targeted ads isn't a good enough reason for the general public to give up the foundation of their every need.

But what if we look beyond the ads? Modern society is changing at such a rapid pace that we often don't realize when we are being taken advantage of. If the convenience or [dopamine rush](https://www.ama.org/publications/MarketingNews/Pages/feeding-the-addiction.aspx) of free services are satisfactory enough, who knows how much we will be willing to compromise to get our fix?

The data that is being collected on you, isn't simply a list of your general interests that advertisers want to know about. The devices that you are using to stay connected to the rest of the world, is being used to track your every move. It is highly probable that a list of companies are aware of your current location and exactly what you are doing while you are reading this. If you use any of Google's services, you are leaving behind a very big digital footprint.

The screenshot below shows a single [personal location](https://support.google.com/accounts/answer/3024190?hl=en) snapshot. This information [isn't being made public](https://privacy.google.com/your-data.html) by Google, but it is being captured without people realizing it. Google continuously captures your exact location that is usually not more than a few meters off.

<p align="center">
  <figure align="center">
    <img src="/img/blog/app_privacy/activity_4.PNG" title="Location" style="border: #404040 2px solid;">
    <figcaption>Image: Personal Location Data as captured by Google.</figcaption>
  </figure>
</p>

By tracking location data this frequently, they can predict things like the activity that you are currently performing.

<p align="center">
  <figure align="center">
    <img src="/img/blog/app_privacy/activity_2.PNG" title="Activity" style="border: #404040 2px solid;">
    <figcaption>Image: Personal Activity Data as captured by Google.</figcaption>
  </figure>
</p>

It can be argued that this is not ethical. It can also be argued that you as a Google user has accepted the terms of service and [privacy policy](https://www.google.com/policies/privacy/), and therefore Google has every right to do the things that you have agreed to. It can be argued that Google is nice enough to actually show you what data they are capturing. They even have an entertaining [timeline](https://www.google.com/maps/timeline?pb) feature that allows you to walk down memory lane and see exactly what you did on any given day.

<p align="center">
  <figure align="center">
    <img src="/img/blog/app_privacy/google_timeline.PNG" title="Timeline" style="border: #404040 2px solid;">
    <figcaption>Image: Reminiscing about a day in Hawaii, thanks to Google. </figcaption>
  </figure>
</p>

The image above, shows my personal activity during a day in Hawaii. It must be noted that, even though I had my phone with me on this day, I did not have any cellular service or WIFI connection throughout the entire day. I do not have an American SIM card, which makes the availability of this data more intriguing.

Android, the Google-developed mobile operating system, has admitted to [tracking users](https://qz.com/1131515/google-collects-android-users-locations-even-when-location-services-are-disabled/), even when a mobile device does not have a SIM card inserted. Cellphone towers are used to send data to Google from Android devices.

A radical solution would be to opt-out of Google services or the more realistic solution would be to trust that Google relies on customer-relations and that they will not try anything to tarnish their reputation.

But what about other mobile apps? In reality, it isn't Google or Facebook who monitors our every move. It is our mobile devices that are serving as chip implants, part of our anatomy, that are telling all apps who are willing to listen, where their users are.

With the Android example (iOS isn't much different), any app developer can include [API calls](https://developer.android.com/training/location/display-address.html) in their app's code that allows them to receive a user's exact location (they can even request the most likely street address of the user's location).

<p align="center">
  <figure align="center">
    <img src="/img/blog/app_privacy/android_address.PNG" title="https://developer.android.com/training/location/display-address.html" style="border: #404040 2px solid;">
    <figcaption> <a href="https://developer.android.com/training/location/display-address.html">Image</a>: The Android Developer's guide on how to capture location data from app users.</figcaption>
  </figure>
</p>

Android's app store, Google Play, is fairly lenient with regards to what app developers do within their apps, as long as they [request permission](https://developer.android.com/training/location/retrieve-current.html) from their users. An app simply has to ask whether they can access your location, messages, photos, etc. and if you agree, they have every right do to so.

A banking app can for instance request your location data. They can make you believe that they need it for something simple, like detecting where the closest branch is, but their terms of service might indicate that they are allowed to use this data to make decisions, such as whether to grant you a loan. The European Union's [General Data Protection Regulation](https://www.eugdpr.org/) is a good initial attempt at regulating this type of activity, but not everyone plays by the rules.

A more malicious case, would be an app with a seemingly innocent purpose, like a photo editor, that is capturing your data with the intent of future blackmailing - essentially serving as ransomware. You may find yourself in a situation where a photo editing app is threatening to reveal evidence to your partner that you have been spending every evening at your ex's place, even though you said you were working late at the office.

Even companies, who truly have the user's best interests at heart, may be causing issues with the data they are capturing without them realizing it. [Strava](https://techcrunch.com/2018/01/28/strava-exposes-military-bases/), a popular fitness app, has been unintentionally revealing the locations of military bases by simply tracking the fitness activities of soldiers who are using their app.

Legally, these app companies are still staying on the straight and narrow by politely asking you whether they may capture your data. But it does not make the more frequently arising privacy issues any less real.

The hand that is feeding us, may be the hand that is sending us to the slaughterhouse. We need to look beyond the comfort food that is being stuffed in our faces. Biting the hand that feeds isn't always a sign of being ungrateful, but sometimes a sign that we disapprove the hidden agenda that is being forced upon us.
