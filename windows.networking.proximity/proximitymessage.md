---
-api-id: T:Windows.Networking.Proximity.ProximityMessage
-api-type: winrt class
---

<!-- Class syntax.
public class ProximityMessage : Windows.Networking.Proximity.IProximityMessage
-->

# Windows.Networking.Proximity.ProximityMessage

## -description
Represents a message that's received from a subscription.

## -remarks
Messages published using the [PublishMessage](proximitydevice_publishmessage.md), [PublishBinaryMessage](proximitydevice_publishbinarymessage.md), or [PublishUriMessage](proximitydevice_publishurimessage.md) methods and received by the [MessageReceivedEventHandler](messagereceivedhandler.md) passed to the [SubscribeForMessage](proximitydevice_subscribeformessage.md) method are of type [ProximityMessage](proximitymessage.md).

## -examples


[!code-csharp[PublishSubscribe](../windows.networking.proximity/code/ProximityReferenceSample/csharp/MainPage.xaml.cs#SnippetPublishSubscribe)]

[!code-js[PublishSubscribe](../windows.networking.proximity/code/ProximityReferenceSample/js/default.js#SnippetPublishSubscribe)]

[!code-vb[PublishSubscribe](../windows.networking.proximity/code/ProximityReferenceSample/vbnet/MainPage.xaml.vb#SnippetPublishSubscribe)]

## -see-also
[Proximity and Tapping (JavaScript)](http://msdn.microsoft.com/library/84a30dcf-ef14-4a93-9e7c-7a3de867d46b), [Proximity and Tapping (C#/VB/C++)](http://msdn.microsoft.com/library/f25bb1df-1cfd-45cd-8c67-04eec73ebfbd), [Proximity sample](http://go.microsoft.com/fwlink/p/?linkid=245082)

## -capabilities
proximity, ID_CAP_PROXIMITY [Windows Phone]
