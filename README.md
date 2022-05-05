<p align="center">
  <a href="https://sentry.io/?utm_source=github&utm_medium=logo" target="_blank">
    <img src="https://sentry-brand.storage.googleapis.com/sentry-wordmark-dark-280x84.png" alt="Sentry" width="280" height="84">
  </a>
</p>

# Sentry pre-configured PHP SDK

[![Monthly Downloads](https://poser.pugx.org/sentry/sdk/d/monthly)](https://packagist.org/packages/sentry/sdk)
[![Latest Stable Version](https://poser.pugx.org/sentry/sdk/v/stable)](https://packagist.org/packages/sentry/sdk)
[![License](https://poser.pugx.org/sentry/sdk/license)](https://packagist.org/packages/sentry/sdk)

This is a metapackage shipping [sentry/sentry](https://github.com/getsentry/sentry-php) with our recommend httpclient.
If you are having troubles with our suggested http layer, please directly install `sentry/sentry` with the http client you prefer.

We recommend:

```
"http-interop/http-factory-guzzle": "^1.0",
"symfony/http-client": "^4.3|^5.0"
```

as the http layer.

Since this is only a meta package, if you are finding this repo and having issues please create an issue on our main repo: [Issue Tracker](https://github.com/getsentry/sentry-php/issues)
