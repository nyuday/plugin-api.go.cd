## Get Plugin Configuration

This is an optional message that the plugin may implement, should users want to configure the plugin from the GoCD admin page. This message allows the server to query a plugin about what properties are supported by this plugin.

<p class='request-name-heading'>Request name</p>

`go.plugin-settings.get-configuration`

<p class='request-body-heading'>Request body</p>

The server will not provide a request body.

<p class='response-code-heading'>Response code</p>

The plugin is expected to return status `200` if it can understand the request.

<p class='response-body-heading'>Response Body</p>

A JSON [plugin settings configuration object](#the-plugin-settings-configuration-object).
