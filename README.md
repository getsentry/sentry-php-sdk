<p align="center">
    <a href="https://sentry.io" target="_blank" align="center">
        <img src="https://sentry-brand.storage.googleapis.com/sentry-logo-black.png" width="280">
    </a>
</p>

# Sentry pre-configured PHP SDK

[![Monthly Downloads](https://poser.pugx.org/sentry/sdk/d/monthly)](https://packagist.org/packages/sentry/sdk)
[![Latest Stable Version](https://poser.pugx.org/sentry/sdk/v/stable)](https://packagist.org/packages/sentry/sdk)
[![License](https://poser.pugx.org/sentry/sdk/license)](https://packagist.org/packages/sentry/sdk)

This is a metapackage shipping [sentry/sentry](https://github.com/getsentry/sentry-php) with our recommend httpclient.
If you are having troubles with our suggested http layer, please directly install `sentry/sentry` with the http client you prefer.

Currently we recommend:

```
"php-http/curl-client": "^1.0",
"guzzlehttp/psr7": "^1.0"
```

as the http layer.

Since this is only a meta package, if you are finding this repo and having issues please create an issue on our main repo: [Issue Tracker](https://github.com/getsentry/sentry-php/issues)