# ADCS2016-Addendum
Microsoft.Windows.Active.Directory.Certificate.Services.2016.Monitoring.Addendum v1.0.0.9

Download [here](https://github.com/theKevinJustin/ADCS2016-Addendum/blob/main/Microsoft.Windows.Active.Directory.Certificate.Services.2016.Monitoring.Addendum.xml)

### Microsoft Windows Active Directory Certificate Services 2016 Monitoring Addendum
Management pack configures rules/monitors, disables noisy rules, adds OCSP seed, OCSP responder and OCSP group (classes), relevant service monitors, service recovery automation

Blog [https://kevinjustin.com/blog/2023/08/18/adcs-addendum-packs/](https://kevinjustin.com/blog/2023/08/18/adcs-addendum-packs/)

# Version History:
```
v1.0.0.9   4 Jan 2024 - Resolution State logic improvements for large environments
v1.0.0.8  27 Dec 2023 - Whitespace audit, added age to monitor reset logic
v1.0.0.7  12 Dec 2023 - Updated reset logic to use Management Pack, removed ID property from reset logic
v1.0.0.6   7 Dec 2023 - Closure and Report logic DS/WA added, Rules, Tasks, StringResource, DisplayStrings
v1.0.0.5  28 Nov 2023 - Updated 7031 DS and ##ADCSServer## regex for groups
v1.0.0.4  18 Jul 2023 - Updated DS script name
v1.0.0.3   9 Jun 2022 - nCipherLog monitor
v1.0.0.2  10 May 2022 - Updates for OcspSvc service and recovery task monitoring
v1.0.0.1  10 Mar 2022 - Updated Certificate override		  
v1.0.0.0  10 Jun 2020 - Created for Windows Server 2016+ ADCS (Certificate Services monitoring for Active Directory) customizations of the sealed pack.
			Includes overrides for rules, new rules for frequent CA events
```
