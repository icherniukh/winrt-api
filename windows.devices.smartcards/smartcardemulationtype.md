---
-api-id: T:Windows.Devices.SmartCards.SmartCardEmulationType
-api-type: winrt enum
---

<!-- Enumeration syntax
public enum Windows.Devices.SmartCards.SmartCardEmulationType : int
-->

# SmartCardEmulationType

## -description
Defines the mechanism by which the device emulates a smart card. Reflects the secure element type of the unit which processes application protocol data unit (APDU) commands.

## -enum-fields
### -field Host:0
The device routes APDU commands to the host application.

### -field Uicc:1
The device routes APDU commands to the UICC card. The UICC card is more commonly referred to as the SIM card.

### -field EmbeddedSE:2
The device routes APDU commands to the Embedded Secure Element.


## -remarks

## -examples

## -see-also
[Create an NFC Smart Card app](http://msdn.microsoft.com/library/26834a51-512b-485b-84c8-abf713787588)
