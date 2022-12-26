# OpenMedia x Rust

## Overview
OpenMedia is defined by the IAB.<br>
See [OpenMedia Specification Suite](https://iabtechlab.com/standards/openmedia/) for more information.


![landscape](https://iabtechlab.com/wp-content/uploads/2016/07/OpenMedia-Specification-Landscape.jpg)

**Layer4 Domain:**<br>
- **TODO** [adcom1]() - [Ad-COM](https://github.com/InteractiveAdvertisingBureau/AdCOM)

**Layer3 Tranasction:**<br>
- [OpenRTB](https://iabtechlab.com/standards/openrtb/)
  - [openrtb-native1](https://crates.io/crates/openrtb-native1) - [OpenRTB Dynamic Native Ads 1.2 Final](https://www.iab.com/wp-content/uploads/2018/03/OpenRTB-Native-Ads-Specification-Final-1.2.pdf)
  - openrtb-conv? [openrtb3-converter](https://github.com/InteractiveAdvertisingBureau/openrtb3-converter)
  - [openrtb2](https://crates.io/crates/openrtb2) - [OpenRTB 2.5 Final](https://iabtechlab.com/wp-content/uploads/2016/07/OpenRTB-API-Specification-Version-2-5-FINAL.pdf)
  - **WIP** [openrtb3]() - [OpenRTB 3.0](https://github.com/InteractiveAdvertisingBureau/openrtb)
 - [OpenDirect](https://iabtechlab.com/standards/opendirect/)
   - opendirect1? - [OpenDirect v1.5.1](https://iabtechlab.com/wp-content/uploads/2016/07/OpenDirect_1-5-1.pdf)
 - AdManagement
   - [Ad Management API v1.0](https://github.com/InteractiveAdvertisingBureau/AdManagementAPI)

**Related Resources:**
- [ads.txt](https://iabtechlab.com/ads-txt/)
  - app-adstxt1? - [app-ads.txt v1.0](https://iabtechlab.com/wp-content/uploads/2019/03/app-ads.txt-v1.0-final-.pdf)
  - [adstxt](https://crates.io/crates/adstxt) - [ads.txt v1.0.2](https://iabtechlab.com/wp-content/uploads/2019/03/IAB-OpenRTB-Ads.txt-Public-Spec-1.0.2.pdf)
- [VAST](https://iabtechlab.com/standards/vast/)
  - vast3? - [VAST v3.0](https://iabtechlab.com/wp-content/uploads/2016/04/VASTv3_0.pdf)
  - [vast4](https://github.com/mechiru/vast4) - [VAST v4.2](https://iabtechlab.com/wp-content/uploads/2019/06/VAST_4.2_final_june26.pdf)

## Related projects
- [prebid/openrtb](https://github.com/prebid/openrtb) — implementation in Golang
