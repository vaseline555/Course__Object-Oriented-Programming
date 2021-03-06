## Sample Input
4  

protocol  

IE?E  

the*  

me*e  

The CAPWAP protocol [RFC5415] defines an extensible protocol to allow an Access Controller to manage wireless agnostic Wireless Termination Points. The CAPWAP protocol itself does not include any specific wireless technologies; instead, it relies on a binding specification to extend the technology to a particular wireless technology.  

This specification defines the Control And Provisioning of Wireless Access Points (CAPWAP) Protocol Binding Specification for use with the IEEE 802.11 Wireless Local Area Network protocol. Use of CAPWAP control message fields, new control messages, and message elements are defined. The minimum required definitions for a binding-specific Statistics message element, Station message element, and WTP Radio Information message element are included.  

Note that this binding only supports the IEEE 802.11-2007 specification. Of note, this binding does not support the ad hoc network mode defined in the IEEE 802.11-2007 standard. This specification also does not cover the use of data frames with the four-address format, commonly referred to as Wireless Bridges, whose use is not specified in the IEEE 802.11-2007 standard. This protocol specification does not currently officially support IEEE 802.11n. That said, the protocol does allow a WTP to advertise support for an IEEE 802.11n radio; however, the protocol does not allow for any of the protocol's additional features to be configured and/or used. New IEEE protocol specifications published outside of this document(e.g., IEEE 802.11v, IEEE 802.11r) are also not supported through this binding, and in addition to IEEE 802.11n, must be addressed either through a separate CAPWAP binding, or an update to this binding.  

In order to address immediate market needs for standards still being developed by the IEEE 802.11 standards body, the WiFi Alliance created interim pseudo-standards specifications. Two such specifications are widely used in the industry, namely the WiFi  
Protect Access [WPA] and the WiFi MultiMedia [WMM] specifications. Given their widespread adoption, this CAPWAP binding requires the use of these two specifications.

## Sample Output
10  

11  

24  

8  

+ Please edit 'input.txt' for another test inputs.
