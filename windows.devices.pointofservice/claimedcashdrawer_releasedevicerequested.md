---
-api-id: E:Windows.Devices.PointOfService.ClaimedCashDrawer.ReleaseDeviceRequested
-api-type: winrt event
---

<!-- Event syntax
public event Windows.Foundation.TypedEventHandler ReleaseDeviceRequested<Windows.Devices.PointOfService.ClaimedCashDrawer,  object>
-->

# Windows.Devices.PointOfService.ClaimedCashDrawer.ReleaseDeviceRequested

## -description
Occurs when the device gets a request to release its exclusive claim.

There is a small window of time (2 seconds) where the app may call [RetainDeviceAsync](claimedcashdrawer_retaindeviceasync.md) to keep exclusive claim. Or alternatively, the app may release claim via [Close](claimedcashdrawer_close.md) to end the window immediately.

## -remarks

## -examples

## -see-also
