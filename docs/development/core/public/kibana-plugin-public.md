<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [kibana-plugin-public](./kibana-plugin-public.md)

## kibana-plugin-public package

## Classes

|  Class | Description |
|  --- | --- |
|  [ToastsApi](./kibana-plugin-public.toastsapi.md) |  |
|  [UiSettingsClient](./kibana-plugin-public.uisettingsclient.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [ApplicationSetup](./kibana-plugin-public.applicationsetup.md) |  |
|  [ApplicationStart](./kibana-plugin-public.applicationstart.md) |  |
|  [BasePathSetup](./kibana-plugin-public.basepathsetup.md) | Provides access to the 'server.basePath' configuration option in kibana.yml |
|  [Capabilities](./kibana-plugin-public.capabilities.md) | The read-only set of capabilities available for the current UI session. Capabilities are simple key-value pairs of (string, boolean), where the string denotes the capability ID, and the boolean is a flag indicating if the capability is enabled or disabled. |
|  [ChromeBadge](./kibana-plugin-public.chromebadge.md) |  |
|  [ChromeBrand](./kibana-plugin-public.chromebrand.md) |  |
|  [ChromeBreadcrumb](./kibana-plugin-public.chromebreadcrumb.md) |  |
|  [CoreSetup](./kibana-plugin-public.coresetup.md) | Core services exposed to the setup lifecycle |
|  [CoreStart](./kibana-plugin-public.corestart.md) | Core services exposed to the start lifecycle |
|  [FatalErrorInfo](./kibana-plugin-public.fatalerrorinfo.md) | Represents the <code>message</code> and <code>stack</code> of a fatal Error |
|  [FatalErrorsSetup](./kibana-plugin-public.fatalerrorssetup.md) | FatalErrors stop the Kibana Public Core and displays a fatal error screen with details about the Kibana build and the error. |
|  [I18nSetup](./kibana-plugin-public.i18nsetup.md) | I18nSetup.Context is required by any localizable React component from @<!-- -->kbn/i18n and @<!-- -->elastic/eui packages and is supposed to be used as the topmost component for any i18n-compatible React tree. |
|  [InjectedMetadataSetup](./kibana-plugin-public.injectedmetadatasetup.md) | Provides access to the metadata injected by the server into the page |
|  [LegacyNavLink](./kibana-plugin-public.legacynavlink.md) |  |
|  [NotificationsSetup](./kibana-plugin-public.notificationssetup.md) |  |
|  [OverlayRef](./kibana-plugin-public.overlayref.md) |  |
|  [OverlayStart](./kibana-plugin-public.overlaystart.md) |  |
|  [Plugin](./kibana-plugin-public.plugin.md) | The interface that should be returned by a <code>PluginInitializer</code>. |
|  [PluginInitializerContext](./kibana-plugin-public.plugininitializercontext.md) | The available core services passed to a <code>PluginInitializer</code> |
|  [PluginSetupContext](./kibana-plugin-public.pluginsetupcontext.md) | The available core services passed to a plugin's <code>Plugin#setup</code> method. |
|  [PluginStartContext](./kibana-plugin-public.pluginstartcontext.md) | The available core services passed to a plugin's <code>Plugin#start</code> method. |
|  [UiSettingsState](./kibana-plugin-public.uisettingsstate.md) |  |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [BasePathStart](./kibana-plugin-public.basepathstart.md) | Provides access to the 'server.basePath' configuration option in kibana.yml |
|  [ChromeHelpExtension](./kibana-plugin-public.chromehelpextension.md) |  |
|  [ChromeSetup](./kibana-plugin-public.chromesetup.md) |  |
|  [HttpSetup](./kibana-plugin-public.httpsetup.md) |  |
|  [HttpStart](./kibana-plugin-public.httpstart.md) |  |
|  [I18nStart](./kibana-plugin-public.i18nstart.md) |  |
|  [InjectedMetadataStart](./kibana-plugin-public.injectedmetadatastart.md) |  |
|  [NotificationsStart](./kibana-plugin-public.notificationsstart.md) |  |
|  [PluginInitializer](./kibana-plugin-public.plugininitializer.md) | The <code>plugin</code> export at the root of a plugin's <code>public</code> directory should conform to this interface. |
|  [ToastInput](./kibana-plugin-public.toastinput.md) |  |
|  [UiSettingsSetup](./kibana-plugin-public.uisettingssetup.md) |  |
