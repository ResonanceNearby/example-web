# Resonance JS SDK example app
#### Resonance Nearby allows you to detect nearby devices across all platforms: Web, iOS and Android.

This app demonstrates how to use Resonance JS SDK in web browser.

You can easily try this app on our [demo page](https://cdn.getresonance.net/examples/web/index.html)
or you can host it on your web server. HTTPS protocol is necessary to get access to microphone.


## How this example works
When page load you will be prompted to input payload. Payload is the data that will be available to all
nearby devices. Search is automatically started after that. When nearby device is detected
line "Found: `another_payload`" will be printed to screen.
Search is stopped when page closed.

You can use this example with example-ios and example-android to see how cross-platform discovery works.

## Creating your own app
Detailed documentation, support and your API-key is available in [Resonance Console](https://console.getresonance.net) after registration.

[Resonance Software](http://www.getresonance.net/)