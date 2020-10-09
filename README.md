# splunk_wineventcode_secanalysis

REQUIRES COMMON INFORMATION MODEL 4.14+ with properly populated signature_id field!

Beta 1.2 of Windows Event Code Security Analysis app for Splunk. Direct questions to brodsky@splunk.com.
Thanks to all security researchers that provided public info on event code recommendations - sources for this
are linked from the Lookup Overview page, Count of Codes by Authority panel.

10-08-20: added Splunk UBA event codes from [Splunk docs](https://docs.splunk.com/Documentation/UBA/latest/GetDataIn/WindowsEvents)

9-14-20: added auto lookup support for XML data sources, added a few new event volume changes to main lookup.

6-11-20: added support in four dashboards for the Event Signatures data model. You must have CIM 4.14+ and you must have accelerated your data in the Event Signatures data model for improved dashboards to work. Windows TA 8.0+ supports population of the critical signature_id field needed.

4-18-20: added Australian Signals Directorate/ACSC's latest event code guidance.
