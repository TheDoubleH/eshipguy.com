---
title: Carrier Tracking URLs
author: Henrik Helgesen
type: page
date: 2011-03-21T19:14:22+00:00
dsq_thread_id:
  - 259679463
dsq_needs_sync:
  - 1

---
Here are a few Tracking URLs as I have found them. Please e-mail me at henrik at eshipguy.com or comment on this down below if you have any issues or you have any you want to share!

As you may notice, some carriers have multiple entries. This happens, when i find better URLs. Knowing that the carriers may retire URLs, I keep older (that may be newer) URLs just for reference. I try to keep my favorite URL as the first entry.

In eShip, the following parameters are used:
- %1: Tracking No [External Tracking No.]
- %2: Ship-To Country [Ship-To Country Code]
- %3: Pickup Date
- %4: Shipping Agent Account No.

## Common Carriers

### UPS

- `https://www.ups.com/track?loc=en_US&tracknum=%1`
- `http://wwwapps.ups.com/WebTracking/track?track=yes&trackNums=%1`
- `http://wwwapps.ups.com/WebTracking/track?HTMLVersion=5.0&loc=en_US&Requester=UPSHome&trackNums=%1&track.x=Track`

### FedEx

- `https://www.fedex.com/fedextrack/?trknbr=>%1`

### USPS

- `https://tools.usps.com/go/TrackConfirmAction?qtc_tLabels1=%1`
- `https://tools.usps.com/go/TrackConfirmAction_input?qtc_tLabels1=%1`
- `http://trkcnfrm1.smi.usps.com/PTSInternetWeb/InterLabelInquiry.do?origTrackNum=%1`

### OnTrac

- `https://www.ontrac.com/trackingresults.asp?tracking_number=%1`
- `http://www.ontrac.com/trackingdetail.asp?tracking=%1`
- `http://www.ontrac.com/tracking.asp?trackingres=submit&tracking_number=%1&trackBtn.x=18&trackBtn.y=12&trackBtn=trackingres_submit`
  
### LaserShip

- `http://lasership.com/track/%1/`
- `http://lasership.com/track/%1/xml` (Returns XML)
- `http://www.lasership.com/track.php?track_number_input=%1`

### DHL US

- `http://www.dhl-usa.com/content/us/en/express/tracking.shtml?brand=DHL&AWB=%1`

### DHL Canada

- `http://international.dhl.ca/content/ca/en/express/tracking.shtml?brand=DHL&AWB=%1`

### DHL Global Mail

- `http://webtrack.dhlglobalmail.com/?trackingnumber=%1`

### Purolator Canada

- `https://www.purolator.com/purolator/ship-track/tracking-details.page?pin=%1`

### TNT

- `http://www.tnt.com/webtracker/tracking.do?navigation=1&searchType=CON&respLang=en&genericSiteIdent=.&cons=%1`

### Royal Mail

- `http://www.royalmail.com/portal/rm/track?trackNumber=%1`
  
### La Poste

- `http://www.colissimo.fr/portail_colissimo/suivre.do?colispart=%1`
  
## LTL Carriers

### AAA Cooper

- `http://www.aaacooper.com/Transit/ProTrackResults.aspx?ProNum=%1`

### ABF

- `https://www.abfs.com/tools/trace/default.asp?hidSubmitted=Y&refno0=%1&reftype0=A`
  
### CAL State Express

- `http://www.calstatexpress.com/scripts/cgiip.exe/protrace.htm?pro=%1&language=&nav=side#`

### Central Freight

- `http://www.centralfreight.com/website/mf/mfInquiry.aspx?inqmode=PRO&pro=%1`

### Central Transport

- `http://www.centraltransportint.com/confirm/trace.aspx?Pro=%1`

### Conway

- `https://www.con-way.com/webapp/manifestrpts_p_app/Tracking/TrackingRS.jsp?pastePros=%1` (Tracking for single or multiple (separated by a comma)

### Dayton Freight

- `http://www.daytonfreight.com/Tracking/TrackingDetail.aspx?proNum=%1`
  
### Estes

- `https://www.estes-express.com/myestes/shipment-tracking/?type=PRO&query=%1`
- `http://www.estes-express.com/cgi-dta/edn419.mbr/output?search_type=F&random_number&hash_value&search_criteria=%1`

### Midwest Motor Express

- `http://www.mmeinc.com/tracking.php?Pro=%1`
  
### Oak Harbor

- `http://www.oakh.com/quicktrace&pro=%1`

### Old Dominion Freight (ODFL)

- `http://www.odfl.com/trace/Trace.jsp?pronum=%1`

### Peninsula

- `http://www.peninsulatruck.com/Tools/FreightStatus.aspx?id=%1`
  
### R&L Carriers

- `https://www2.rlcarriers.com/freight/shipping/shipment-tracing?pro=%1&docType=PRO&source=web`

### Roadrunner

- `http://tools.rrts.com/LTLTrack/?searchValues=%1`
- `https://www.rrts.com/Tools/Tracking/Pages/MultipleResults.aspx?PROS=%1`

### Roadway / Yellow (aka yrc) (RDWY)

- `https://my.yrc.com/tools/track/shipments?referenceNumberType=PRO&referenceNumber=%1`
- `http://my.yrc.com/dynamic/national/servlet?CONTROLLER=com.rdwy.ec.rextracking.http.controller.ProcessPublicTrackingController&PRONumber=%1`

### Priority Solutions

- `https://www.paxtracks.com/TrackingQuery.asp?c=[Customer Group]%20&u=[USER ID]&p=[Password]&f=B&v=OA%1`

### SAIA

- `http://www.saia.com/Tracing/AjaxProstatusByPro.aspx?nh=N&Pro=%1`
- `http://www.saia.com/Tracing/AjaxProstatusByPro.aspx?&PRONum1=%1`

### Southeastern Freight Lines

- `https://www.sefl.com/webconnect/tracing?Type=PN&RefNum1=%1`

### UPS LTL

- `http://ltl.upsfreight.com/tracking/ShipTrack.aspx?ProNbr=%1`
  