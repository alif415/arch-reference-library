# Reference Model: End-user Devices Model

<!--TOC max3-->

## Purpose

An architecture reference model is an abstract framework or domain-specific ontology consisting of an interlinked set of clearly defined concepts produced by an expert or body of experts in order to encourage clear communication. This frame of reference can then be used to communicate ideas clearly among members of the architecture and/or delivery community.

The purpose of this model is to describe the classes of end-user device that a Scottish public sector organisation may need to support when delivering *digital* public services.


## Revision History

| Version | Issued     | Comments
| ---     | ---        | ---
|     0.1 | 10-06-2016 | Initial draft created.


## Distribution List

| Role                         | RACI
| ---                          | ---
| Technical Solutions Lead     | Responsible
| Head of Digital Architecture | Accountable
| Technical Director           | Consulted
| Infrastructure Manager       | Consulted


## Review

| Review frequency | Next review due
| ---              | ---
| 6 months         | 10-12-2016

N.B. this model will be reviewed and updated to reflect our evolving understanding of digital public services.


## Role

The purpose of this model is to describe the classes of end-user device that a Scottish public sector organisation may need to support when delivering *digital* public services.

This model has the specific role of:

- providing a consitent language to use when discussing end-user devices;
- describing some of the major aspects by which end-user devices vary;
- making recommendations as to how organisations should ensure their services are available across a broad range of devices.

This model relates directly to the aims of the "[Scotland’s Digital Future: Delivery of Public Services](http://www.gov.scot/Publications/2012/09/6272)" strategy as follows:

> Public services will be:
>
> - available online wherever they can be so
> - accessible through a wide range of devices from, for example, computers, smartphones and televisions
> - accessible through a single, though not exclusive, point of entry to public services to help navigate through the public sector landscape
> - available with assisted access to take into account the differing capacities of users, including by telephone or face-to-face.”


## Scope

- [ ] Foundation
- [ ] Common Systems
- [ ] Industry
- [x] Org-specific

This model is specifically applicable to the Scottish Central Government family however it could be applied to the wider public sector and other sectors with adaptation.


## Taxonomy

End-user
: End-users are the consumers of digital services provided by Scottish public sector organisations. They are typically citizens or businesses.

Mobile Device
: Mobile devices are computing devices that have been designed specifically for the purposes of portability. They are typically small form factor, lightweight and include an integrated battery as well as a touch screen. They also often include an operating system tailored specifically with mobility in mind. Examples of mobile devices include tablets, feature phones and smart watches.

Desktop Device
: Desktop devices are general purpose computing devices that are designed primarily for use within a home or office setting and often when sitting at a desk. These devices are typically larger in form factor than mobile devices, operate a standard operating system and are driven using a keyboard and mouse (or trackpad). Examples of desktop devices include standard PCs and laptops.

Specialised Device
: Specialised devices includes all devices that are not mobile or desktop devices. These devices are typically designed for a specific purpose; or computing capabilities that exist as a secondary feature of the device. These devices often run specialist operating systems, have bespoke peripherals and may include specialist hardware. Examples of specialist devices include smart televisions, games consoles and many other devices that make up the internet of things.

Native Application
: Native applications are software applications that run directly on a device's operating system and this means that they are normally developed for a specific platform. They typically have direct access to the device's underlying hard disk, camera, GPS and other physical components. Native applications require some sort of installation process and, more recently, they are usually downloaded from an app store or other managed directory. Native applications will normally work when the device is offline.

Web Browser
: A web browser is a native application designed to allow end-users to access the world wide web and, often, other parts of the internet. A vast range of web browsers are available across mobile, desktop and specialist devices. At a minimum a web browser will support HTTP(S), DNS, HTML, CSS & Javascript standards, however, the range and quality of this support can vary dramatically across different devices. The term 'mobile browser' is typically a shorthand for saying a web browser running on a mobile device and, similarly 'desktop browser' typically means a web browser running on a desktop device.

Web Site
: A web site is a collection of documents that are available at a specific web domain, accessed using a web browser. Web sites are primarily static assets focused on informational content rather than complex interactions. End-users navigate amongst the various pages on a web site using hyperlinks.

Web Application
: Web applications operate similar to web sites in that they are accessible at a web domain and are accessed with a web browser. However, rather than simply serving static documents to provide information a web application will typically include complex "server side" logic that provides a more complex interaction or transaction processing on behalf of end-users. Within the context of digital public services these transactions might include applying for permission, making a payment, etc.

Hybrid Native Application
: Hybrid native applications are a special class of native applications that are comprised of a common shell, running directly on a device's operating system, which then hands off to an embedded web browser or other web control. The bespoke application logic is implemented using HTML, CSS and Javascript running within the embedded browser. Hybrid applications must be installed in a similar way to other native applications and can also typically access the device's underlying resources such as file system, camera and GPS. Hybrid app's allow web developers to re-use their existing skills to build native applications. Examples of hybrid application shells include [Electron](http://electron.atom.io) (for desktop devices) and [PhoneGap](http://phonegap.com) (for mobile devices).

Progressive Web applications
: Progressive web applications are a special class of web applications that behave in a way that is more similar to native applications. This typically means that the progressive web app has an icon on the device's home screen and executes in a separate process rather than simply as a tab in the device's standard web browser. Progressive web applications stay fresh in the same way as standard web applications as no complex installtation is required. Progressive web applications can take advantage of some device capabilities such as push notifications and can work offline if engineered correctly. Examples of progressive web applications include the [Financial Times App' for iOS](http://apps.ft.com/home/web-app/) and the [Flipboard Web App'](https://flipboard.com).

Browser Plugin
: Browser plugins allow the standard capabilities of web browser to be extended. Plugins typically run directly on a device's operating system in similar way to native applications. Browser plugins were popular in the early days of the web when browser included only a basic feature set and web standards such as HTML included only basic capabilities. However, things have moved on considerably and the need for plugins has diminished significantly. Because browser plugins run with increased privileges compared to regular web sites and web applications they can pose a significant security threat if not implemented correctly. Popular browser plugins include [Adobe Flash Player](https://www.adobe.com/products/flashplayer.html) and [Oracle Java Plugin](http://www.oracle.com/technetwork/java/index-jsp-141438.html).

Mobile First
: Mobile first is an approach for the development of web sites and web applications that aims to deliver better compatibility across a range of devices (mobile, desktop and specialist) and with reduced effort on the part of the development team. The basis of this approach is to prioritise the development of the site or application with full compatibility in one or more mobile browsers. This approach relies on the fact that both the features and level of standards compliance on mobile browsers has historically lagged behind that of desktop counterparts. Therefore, the chance of a site or application developed to be compatible with mobile browsers also being compatible with desktop browsers is more likely than vice versa. Complementary to this, mobile devices offer an additional set of design constraints that do not exist on desktop; for example reduced screen size and limited network bandwidth. Focusing on addressing these constraints early in the development processes increases the likelihood of a succesful outcome.


## Graphic

![End-user Devices Graphic](dpsbt-end-user-devices-graphic.png)


## Discussion

### The end-user device landscape

Users no longer access digital services exclusively from desktop devices. They use a range of desktop, mobile and specialist devices to access online services both within the home and on the move.

Mobile device ownership is now widespread. [Ofcom analysis](http://media.ofcom.org.uk/facts/) indicates that, as of Q1 2015, 93% of adults in the UK personally own/use a mobile phone and 66% of adults own a smartphone. Furthermore, smartphones have become a crucial access point for people coming online. Google's [analysis of The Connected Consumer Survey](https://www.consumerbarometer.com/en/trending/?countryCode=UK&category=TRN-NOFILTER-ALL) found that in the UK in 2015 61% of people access the internet at least as often via smartphone as computer and that 42% of people surveyed use at least three devices - computer, smartphone and tablet.

The mygov.scot website provides an example of this trend towards mobile use, with over 40% of all visitors coming from mobile phones.

Complementary to this the device landscape is becoming more complex:

- the variety of devices in the hands of end-users (and therefore that we are required to support) is increasing rather than decreasing over time;
- the capabilities of new devices is increasing over time.

Finally, users expectations of the quality of digital public services, especially those they can access on mobile and specialist devices, is increasing over time as they are exposed to high quality commercial services.

### Web app's vs. native app's

#### Native app's

Pros:

- Persistent presence on device;
- Can access all functions on a device (camera, accelerometer, etc.);
- Acceptable performance for services that store large volumes of data or undertake complex comutation;
- Can be used offline, in some cases;
- A ‘download and buy’ revenue stream available.

Cons:

- Often need to maintain a separate app for each mobile platform (and in some case maintain separate app's for different platform versions);
- Each platform requires specialist skills to support development (e.g. Objective C for iOS, Java for Android, etc.) making them more expensive to develop & maintain;
- Development iterations more complex;
- Slower to update (via gatekeeper app stores) therefore cycle times are extended, impeding continuous improvement;
- More effort for user to get installed and actually get value therefore, native app's must be used frequently for end-users to invest the effort in installing them.

#### Web App's

Pros:

- General purpose skills (HTML, JS, etc.) makes it easier for existing web developers as well as non-developers to contribute;
- Simpler technology estate to manage;
- No gatekeepers to constrain access or installation required;
- Uses open standards means less vendor lock in;
- It allows you to iterate your services much more quickly;
- Low cycle time makes it faster and simpler to continuously improve the service;
- Acceptable performance for 'utility' services;
- Cheaper to support.

Cons:

- App's not persistent on device;
- Some device features unavailable (camera, address book);
- Typically requires internet connection;
- Unacceptable performance for some services that store large volumes of data, undertake complex comutation or require complex animation / graphical acceleration;
- No ‘download and buy’ revenue stream.

### Recommendations

On the basis of the above discussion we currently recommend the following approach to delivering digital public services across a range of end-user devices:

- By default build web applications based on open standards;
- Establish a robust service delivery capability that includes a strong mix of automated and exploratory testing across a range of simulated and real devices;
- Establish compatibility requirements early and articulate these in terms of device capabilities rather than specific combinations of browser and operating system;
- Make use of modern web development practices such as mobile first, responsive web design and progressive enhancement to reduce the effort required to support your applications on new devices and browsers;
- Avoid creating, or depending on, browser plugins;
- Where an additional capability is required that cannot be satisifed by a web application first consider a progressive web application and then a hybrid native application before embarking on full native app development;
- Avoid implementing native applications.

### When is a native application appropriate

It is our view that native applications are **very** rarely justified and that as web capabilities improve the circumstances where a native app is required continue to diminish. Interactions with many public services occur infrequently or irregularly and installing a native app is an unnecessary barrier to citizens accessing these services. Furthermore, we believe the benefits of developing and maintaining a native app will very rarely justify its cost.

At present some circumstances that **may** justify a native app include:

- access is required to specialist hardware such as the device's camera, accelerometer, GPS, etc.;
- a 24/7 presence of the app on a user's device is required;
- long periods without internet connectivity must be tolerated;
- complex computation must be unertaken on the device itself, rather than on a server;
- access is required to specialist SDKs and APIs such as those for health tracking or home automation etc;
- very large volumes of data must be stored and processed on the device.

For general purpose digital public services GDS have provided the following questions to consider before initiating the development of a native app, and these are also relevant in a Scottish context:

1. Is your web application already designed to be responsive? If not, why not?
2. What is the user need that only a native/hybrid App can meet?
3. Are there existing native/hybrid apps which already meet this user need?
4. Is your service available to 3rd parties via API or open data? If not, why not?
5. Does meeting this need justify the lifetime cost of native or hybrid app?

In particular, native apps should only be considered once the core web application works well on mobile devices.


## References

- [GDS Blog Post: "We're not ‘appy. Not ‘appy at all."](https://gds.blog.gov.uk/2013/03/12/were-not-appy-not-appy-at-all/)
- [Ofcom Communications Market Report 2015: Scotland](http://stakeholders.ofcom.org.uk/market-data-research/market-data/communications-market-reports/cmr15/scotland/)
