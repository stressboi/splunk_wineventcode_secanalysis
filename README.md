# splunk_wineventcode_secanalysis

REQUIRES COMMON INFORMATION MODEL 4.14+ with properly populated signature_id field!

Version 1.4 of Windows Event Code Security Analysis app for Splunk. Direct questions to brodsky@splunk.com.
Thanks to all security researchers that provided public info on event code recommendations - sources for this
are linked from the Lookup Overview page, Count of Codes by Authority panel.

If you want a .spl version of this look in the root of this repo - removed temporarily but will put it back soon!

1-27-20: Fixed lookup link to ACSC guidance.

1-12-20: Fixed a bug with missing host input, fixed drilldowns from timecharts.

1-07-20: updated lookup for code 1007,1200,1202,307,510.

12-25-20: added Golden SAML event code guidance.

10-09-20: added an option to specify index wildcards.

10-08-20: added Splunk UBA event codes from [Splunk docs](https://docs.splunk.com/Documentation/UBA/latest/GetDataIn/WindowsEvents) - thank you @drewchurch.

9-14-20: added auto lookup support for XML data sources, added a few new event volume changes to main lookup.

6-11-20: added support in four dashboards for the Event Signatures data model. You must have CIM 4.14+ and you must have accelerated your data in the Event Signatures data model for improved dashboards to work. Windows TA 8.0+ supports population of the critical signature_id field needed.

4-18-20: added Australian Signals Directorate/ACSC's latest event code guidance.
