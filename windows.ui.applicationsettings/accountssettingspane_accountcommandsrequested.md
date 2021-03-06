---
-api-id: E:Windows.UI.ApplicationSettings.AccountsSettingsPane.AccountCommandsRequested
-api-type: winrt event
---

<!-- Event syntax
public event Windows.Foundation.TypedEventHandler AccountCommandsRequested<Windows.UI.ApplicationSettings.AccountsSettingsPane,  Windows.UI.ApplicationSettings.AccountsSettingsPaneCommandsRequestedEventArgs>
-->

# Windows.UI.ApplicationSettings.AccountsSettingsPane.AccountCommandsRequested

## -description
Occurs when the user opens the accounts pane. Handling this event lets the app initialize the accounts commands and pause its UI until the user closes the pane.

## -remarks
When your app handles this event, populate the provided [AccountsSettingsPaneCommandsRequestedEventArgs](accountssettingspanecommandsrequestedeventargs.md) with your [SettingsCommand](settingscommand.md) objects, your [CredentialCommand](credentialcommand.md) objects, and your [WebAccountCommand](webaccountcommand.md) objects to make them available to the [AccountsSettingsPane](accountssettingspane.md)UI.

## -examples

## -see-also
