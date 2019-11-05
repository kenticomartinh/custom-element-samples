# Custom app host

This is a wrapper for a general web application which allows's it to load as custom app in Kentico Kontent without fulfilling the custom app contract.

# Usage

If you want to use the Custom app host in your project in Kentico Kontent, follow these steps:

* In Kentico Kontent add **Custom app**
* Use following URL as Hosted code URL (HTTPS): https://kentico.github.io/kontent-custom-element-samples/CustomAppHost/custom-app-host.html
* Provide the following JSON parameters for the custom app:

```
{
    "appUrl": "<HOSTED_APP_URL>",
}
```

Note: You can use a macro `##PROJECTID##` within the `appUrl` to populate it with the currently selected project ID.

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/kontent-custom-element-samples/CustomAppHost?pixel)
