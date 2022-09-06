SensioDistributionBundle
========================

If you want to use Composer 2 with Symfony 3, you can use that buundle.

In your composer.json, replace:
```
    "sensio/distribution-bundle": "^5.0",
```

By:
```
    "sensio/distribution-bundle": "dev-master",
```

And add the following in your repositories:

```
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/ninsuo/SensioDistributionBundle-composer2"
    }
]
```