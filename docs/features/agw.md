---
layout: page
---

# SECURITY
- NAS keys generation and integrity protection and encryption of NAS
signaling
- Support for NAS Integrity protection algorithms - Null, Snow3G and AES
- Support for NAS encryption/decryption algorithms- Null
- eNB key generation and distribution to eNB to manage AS security
- Permanent identity protection via temporary identity allocation for the subscriber
 
## SUBSCRIBER SUPPORTED FEATURES
- LTE Subscriber Registration for both EPS and Non-EPS services (CS voice and CS-SMS)
- LTE Subscriber mutual authentication via EPS-AKA mechanism
- LTE Subscriber authorization
- IP address allocation to the subscriber
- Pull the subscriber profiles (APN, Subscribed QoS etc) from HSS during registration
- Update the current serving MME id for the subscriber to HSS. 
- Get the charging policy and QoS policy (PCC Rules and Rating groups) from PCRF for the subscriber and enforce the same on data flows.
- Get the allowed data grant from the OCS for different rating groups for the subscriber and enforce the same on data flows.
- Mobile broadband data service over default EPS bearer and enforcement of charging and QoS policy at flow level.
- Managing the transition of subscribers between connected and idle state
- Handle service request from subscribers to move the subscribers to connected state to handle outgoing signaling/data.
- Page subscribers to move the subscribers to a connected state to handle incoming signaling/data.
- Track the inactive subscribers and de-registers inactive subscribers from the system.
- Support subscriber initiated de-registration request.
- Support HSS initiated subscriber de-registration request.
 
# VOICE OVER LTE SUPPORTED FEATURES
- VoLTE - PDN connection toward IMS to support VoLTE.
- VolTE - Support for multiple EPS bearers (default and dedicated EPS bearer) within one PDN connection to support VoLTE.
- VoLTE and Data - Multiple PDN/APN connections to support VoLTE and Internet services simultaneously.
 
