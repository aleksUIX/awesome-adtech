# Awesome AdTech [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source projects for adtech, programmatic advertising, ad serving, measurement, VAST, and CTV.

This list stays close to code you can run, embed, extend, or learn from. The focus is on open-source projects rather than closed vendor product pages, marketing sites, or paper-only repositories. It favors maintained projects and historically important foundations over one-off experiments and thin wrappers.

## Contents

- [Auction Engines and Ad Servers](#auction-engines-and-ad-servers)
- [Header Bidding and Prebid](#header-bidding-and-prebid)
- [OpenRTB and Protocol Libraries](#openrtb-and-protocol-libraries)
- [Video Ads, VAST and CTV](#video-ads-vast-and-ctv)
- [Programmatic Direct and Deal Automation](#programmatic-direct-and-deal-automation)
- [Identity, Privacy and Supply Chain Transparency](#identity-privacy-and-supply-chain-transparency)
- [Measurement, Analytics and Optimization](#measurement-analytics-and-optimization)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

## Auction Engines and Ad Servers

- [RTBKit](https://github.com/rtbkit/rtbkit) - Open-source toolkit for building and deploying real-time bidders for display advertising.
- [vanilla-rtb](https://github.com/venediktov/vanilla-rtb) - C++ demand-side bidding framework for low-latency OpenRTB auctions.
- [OpenSSP](https://github.com/ad-tech-group/openssp) - Open-source supply-side platform with OpenRTB support.
- [Zhuque](https://github.com/javagossip/zhuque) - Open ad platform that bundles SSP, ADX, DSP, and DMP modules.
- [ethical-ad-server](https://github.com/readthedocs/ethical-ad-server) - Privacy-friendly ad server built for developer-focused ads without behavioral tracking.

## Header Bidding and Prebid

- [Prebid.js](https://github.com/prebid/Prebid.js) - The standard open-source client-side header bidding framework.
- [Prebid Server](https://github.com/prebid/prebid-server) - Server-side auction engine for running real-time header bidding in the cloud.
- [Prebid Server Java](https://github.com/prebid/prebid-server-java) - Java implementation of Prebid Server.
- [Prebid Mobile Android](https://github.com/prebid/prebid-mobile-android) - Android SDK for bringing Prebid demand into mobile apps.
- [Prebid Mobile iOS](https://github.com/prebid/prebid-mobile-ios) - iOS SDK for bringing Prebid demand into mobile apps.
- [ArcAds](https://github.com/washingtonpost/ArcAds) - Publisher-oriented wrapper around Google Ad Manager / DFP with header bidding support.
- [dfp-prebid-setup](https://github.com/kmjennison/dfp-prebid-setup) - Automated line item generator for Prebid.js and Google Ad Manager.

## OpenRTB and Protocol Libraries

- [prebid/openrtb](https://github.com/prebid/openrtb) - Go types for OpenRTB 2.x, 3.0, AdCOM 1.0, and Native 1.2.

## Video Ads, VAST and CTV

- [vast-client-js](https://github.com/dailymotion/vast-client-js) - JavaScript library for parsing VAST documents.
- [vast-parser](https://github.com/unruly/vast-parser) - Resolves and parses chained VAST documents into a single object.
- [rmp-vast](https://github.com/radiantmediaplayer/rmp-vast) - Client-side JavaScript loader, parser, and renderer for VAST 2, 3, and 4 in HTML5 video.
- [php-vast](https://github.com/sokil/php-vast) - PHP library for generating and parsing VAST documents.
- [haxqer/vast](https://github.com/haxqer/vast) - Go library for generating and parsing VAST 4.2 payloads.
- [madman-android](https://github.com/flipkart-incubator/madman-android) - Android media ads manager for rendering VAST ads without the standard IMA SDK.
- [threefive](https://github.com/superkabuki/threefive_is_scte35) - SCTE-35 parser and encoder for ad break signaling in CTV and OTT workflows.
- [VAST-Tester](https://github.com/IABTechLab/VAST-Tester) - IAB Tech Lab's React-based VAST testing application for exercising video ad tags and player behavior.
- [SHARC](https://github.com/IABTechLab/SHARC) - Secure HTML Ad Richmedia Container standard and reference materials for cross-platform rich media ads.
- [vastlint](https://github.com/aleksUIX/vastlint) - Spec-first VAST validator and linter with CLI, web, and MCP interfaces.

## Programmatic Direct and Deal Automation

- [buyer-agent](https://github.com/IABTechLab/buyer-agent) - IAB Tech Lab reference buyer-side agent for OpenDirect 2.1 media buying, negotiation, and deal booking.
- [seller-agent](https://github.com/IABTechLab/seller-agent) - IAB Tech Lab reference seller-side agent for media kits, pricing, deal negotiation, and Deals API distribution.

## Identity, Privacy and Supply Chain Transparency

- [id5-api.js](https://github.com/id5io/id5-api.js) - Publisher-facing JavaScript API for ID5's privacy-aware universal identifier.
- [adstxtcrawler](https://github.com/InteractiveAdvertisingBureau/adstxtcrawler) - IAB reference crawler for Ads.txt discovery and validation workflows.
- [ads.txt-parser](https://github.com/InteractiveAdvertisingBureau/ads.txt-parser) - IAB reference parser for ads.txt and app-ads.txt processing.
- [10up/ads-txt](https://github.com/10up/ads-txt) - WordPress plugin for managing ads.txt and app-ads.txt files.
- [ads.txt](https://github.com/perry-mitchell/ads.txt) - JavaScript parser and generator for ads.txt files.
- [adscrawler](https://github.com/appgoblin-dev/adscrawler) - Crawler for app stores, SDKs, and app-ads.txt discovery.
- [iab-mapper](https://github.com/IABTechLab/iab-mapper) - Local IAB content taxonomy mapper with OpenRTB- and VAST-ready output.
- [iabgpp-es](https://github.com/IABTechLab/iabgpp-es) - TypeScript library for encoding, decoding, and exposing the IAB Global Privacy Platform string and APIs.
- [iabgpp-java](https://github.com/IABTechLab/iabgpp-java) - Java library for encoding and decoding GPP consent strings and related privacy sections.
- [uid2-operator](https://github.com/IABTechLab/uid2-operator) - Core server implementation for Unified ID 2.0 token generation and operator workflows.

## Measurement, Analytics and Optimization

- [advertools](https://github.com/eliasdabbas/advertools) - Python toolkit for online marketing, SEO, and advertising analysis.
- [AppGoblin](https://github.com/appgoblin-dev/appgoblin) - App store analytics focused on ad networks, trackers, and MMP visibility.
- [DeepRec](https://github.com/DeepRec-AI/DeepRec) - High-performance recommendation framework useful for ranking and personalization workloads in ads systems.
- [Multitask-Recommendation-Library](https://github.com/easezyc/Multitask-Recommendation-Library) - PyTorch implementations of multi-task recommendation models and datasets.

## Related Awesome Lists

- [AirGrid/awesome-adtech](https://github.com/AirGrid/awesome-adtech) - Community-curated list of adtech links and tools.
- [cenoura/awesome-ads](https://github.com/cenoura/awesome-ads) - Advertising resources covering ad ops, ad servers, programmatic, and validation.
- [vanilla-rtb/awesome-rtb](https://github.com/vanilla-rtb/awesome-rtb) - RTB-focused list of frameworks, engines, and related resources.
- [jshorwitz/awesome-agentic-advertising](https://github.com/jshorwitz/awesome-agentic-advertising) - AI-agent and MCP tooling for advertising workflows.

## Contributing

Pull requests are welcome.

Good additions usually have all of the following:

- Public source code, not just docs or a landing page.
- Clear relevance to adtech, advertising infrastructure, measurement, identity, VAST, or CTV.
- Enough implementation depth to be useful as a library, service component, SDK, validator, or reference system.
- Evidence of maintenance or clear historical importance to the ecosystem.

Please avoid adding closed SaaS products, vendor profile mirrors, or thin wrappers with no meaningful source.