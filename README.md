# ExpressVPN Digital Security Lab
## Investigation: Telehealth apps for opioid addiction treatment and recovery

This repository contains the results of a July 2021 investigation into Android apps that are utilized for opioid addiction treatment and recovery. This research was conducted by Sean O'Brien of the [ExpressVPN Digital Security Lab](https://expressvpn.com/digital-security-lab) with the aid of Esther Onfroy of the [Defensive Lab Agency](https://defensive-lab.agency). Findings are described on [our website](https://www.expressvpn.com/digital-security-lab/opioid-telehealth-research).

We encourage users to independently validate the investigation results. This information is released for consumer awareness only and should be interpreted by security professionals.

## Quick Links

**Consumers:** Consult our [findings summary](all_apps.md).

**Researchers:** Consult the files below.

* [All Apps](all_apps.md): [JSON](all_apps.json) | [CSV](all_apps.csv) - Findings for all apps
* [SDK Signatures](sdk_signatures.md): List of SDK signatures identified in apps

## Apps Analyzed

* [Bicycle Health](bicycle-health/): `bicycle-health_1.0.5.apk`        
* [Boulder Care](boulder-care/): `boulder-care_1.141.0.apk`        
* [Confidant Health](confidant-health/): `confidant-health_2.0.14.apk`     
* [DynamiCare Health](dynamicare-health/): `dynamicare-health_1.0.186.apk`  
* [Kaden Health](kaden-health/): `kaden-health_21.3.30.apk`        
* [Loosid](loosid/): `loosidapp_3.8.20.apk`
* [Pear Reset-o](pear-reset-o/): `pear-reset-o®_1.6.1.apk`
* [PursueCare](pursuecare/): `pursuecare_1.0.0.apk`
* [Sober Grid](sober-grid/): `sobergrid_3.3.82(212).apk`
* [Workit Health](workit-health/): `workit_1.8.0.apk`

## Directory Structure

Inside every directory of findings about each app, you will find: 

* `*.apk.256sum`: SHA-256 checksum for the Android APK installer 
* `call-graphs` directory: Call graphs for the Android app in digraph and PNG format
* `exodus-report.json`: [Exodus Privacy](https://exodus-privacy.eu.org) report in JSON format 

## Contact

If you have any questions or suggestions regarding these findings, email us at digital-security-lab@expressvpn.com.
