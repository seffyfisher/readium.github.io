---
layout: page
permalink: "/about/faq.html/"
title: Readium FAQ
---

The FAQs below are divided into categories (General, Readium Foundation, Readium.js, Readium Chrome Application and the Cloud Reader, Readium SDK, and Readium LCP).

 

### General

How can I help the Readium projects?

- There are **many** ways to help the Readium projects. You don’t have to be a developer or publishing guru.  If you have these skills and want to help, you are of course very welcome!  But we also have great needs for testers, documentation, translators and many other areas.  If you want to help please [contact us](mailto:rkwright@readium.org)!

 

### The Readium Foundation

What is the relationship between Readium and standards bodies such as the IDPF and W3C?

- In early 2017, IDPF  combined with the World Wide Web Consortium (W3C), which is responsible for HTML and other Web Standards, thus standards development for EPUB and other publishing technology for the Web Platform is now taking place within W3C. For more information see Publishing@W3C [ link to https://w3.org/publishing]. A number of Readium Foundation members and contributors are participating in Publishing@W3C activities to help ensure coordination. 
- Governance of Readium Foundation is by board of directors elected by representatives of its member organizations.



### The ReadiumJS Project

What is the status of cross-browser support in Readium.js?

- Readium.js is architected to work on any modern (HTML5) browser. The Readium Chrome Application obviously only functions in the Google Chrome browser. However, the Readium Cloud Reader is a full EPUB 3 implementation that runs in Google Chrome, Firefox, Safari, Microsoft Edge and Opera on essentially all platforms supported by those browsers.  However, given the huge matrix of browsers and platforms, Readium is working hard to ensure that the functionality is equivalent across all the platforms.  That is very difficult and Readium welcomes all who would report problems or, even better, help us make our support more complete.

 

### The Readium Chrome Application and the Cloud Reader

Is the Readium Chrome Application a consumer-grade EPUB reading system?

- The original intent of the Readium Chrome application was  to be used primarily by authors, publishers, and developers creating and testing EPUB 3 content and tools. However the Readium Chrome Applicatio had almost 10,000 active users (as of February 2016) and has been translated into 11 languages with the help of our contributors, so clearly we have exceeded that expectation.  That said, there is more to be done to make it a full-fledged EPUB reader.  While RCA supports almost all of the EPUB 3.0.1 standard, there are still some missing features (e.g. a sortable library, annotations, search, etc.), but  the Readium Foundation intends to continue expanding and supporting it in the future..

Will the Readium Chrome Application or Cloud Reader open DRM-protected eBooks?

- At this time there are no plans for Readium Chrome Application to support DRM-protected eBooks.

Will the Readium Chrome Application or Cloud Reader support other publication formats besides EPUB?

- Not at this time. We have considered supporting PDF, but as an open-source effort we are dependent on volunteers to provide the resources for such undertaking.  At present, such an effort is not in our scope.

Are the Readium Chrome Application and Cloud Reader accessible?

- Yes! Basic accessibility support has been implemented.  We are continuing to work actively on improving that support.  Readium welcomes all reports of areas where we can improve our support and especially welcome any contribution to its development and testing.

Are the Readium Chrome Application and the Cloud Reader localized to languages besides English?

- Yes, 11 languages are currently available for both the Chrome Application and the Cloud Reader. Contributions of translation assistance are very welcome, as an internationalization infrastructure is in place.  If you wish to help, please contact us by email.

Do the Readium Chrome Application, Cloud Reader and Readium SDK share source code?

- Yes, the Cloud Reader and the Chrome Application share almost all their source code, the primary difference being that the Chrome Application is naturally packaged as a Chrome Application. The Chrome Application, Cloud Reader and SDK also share a large section of their code, written in JavaScript.

Can I deploy the Cloud Reader on my own site?

- Yes!  And it is very easy.  Please see the instructions [here](https://github.com/readium/readium-js-viewer).  If you have problems or questions, please contact us via email or find us on Slack (instructions here).



## The Readium SDK

Do I have to obtain a commercial license to use the Readium SDK?

- **No!** Effective January, 2018 all Readium SDK software is **permissively licensed, completely free of charge** under the [3-part BSD license](https://github.com/readium/readium.github.io/blob/master/license.txt) and the previous fee-based license is no longer offered. 
- Adopters are encouraged to help support Readium SDK development and maintenance by paying an _optional_ annual support fee. 

Does the SDK support DRM?

- Yes, it does but the SDK is DRM-agnostic. This means the SDK has been developed so it can be used with many different kinds of DRM-encrypted books or no DRM at all.  No DRM at all is the default.  
- Readium of course supports [Readium LCP]([LCP FAQ](https://www.edrlab.org/readium/readium-lcp/faq/))). For other DRMs, the support must be added by the vendor and is specific to their particular application,

Does the SDK support other book formats than EPUB?

- Not at this time. We have considered supporting PDF, but as an open-source effort we are dependent on volunteers to provide the resources for such undertaking.  At present, such an effort is not in our scope.

## The Web Publishing Manifest

The Web Publishing Manifest is now available on the Readium github repository here.  But you can access the JSON-LD Contexts right here:

The default context is [here](https://cdn.rawgit.com/readium/webpub-manifest/64ed37e0/contexts/default/context.jsonld)
The EPUB context is [here](https://cdn.rawgit.com/readium/webpub-manifest/64ed37e0/contexts/epub/context.jsonld)

## The Readium LCP

Please see the [LCP FAQ](https://www.edrlab.org/readium/readium-lcp/faq/)