
# Troubleshooting deployments

Issues with deployments on Umbraco Cloud often come down to a misunderstanding on how to work with Umbraco Cloud. It is very important to always work left to right as mentioned [here](../../deployment/README.md).

There are two ways to deploy on Umbraco Cloud, a deployment that transfers content and media:

1. A Content [Transfer](../../deployment/content-transfer.md) / [Restore](../../deployment/restoring-content/README.md)
1. A [Deployment](../../deployment/cloud-to-cloud.md) that transfers structure files (doc types, data types, templates, dll's, etc.)

There are some common errors associated with both of these, most of the time it is caused by conflicting [UDA files](../../set-up/power-tools/generating-uda-files.md#what-are-uda-files) between the two environments you are deploying between.

The most common [Deployment](../../deployment/cloud-to-cloud.md) issues are listed below with guides on how to fix them:

* [Collision Errors](structure-error.md)
* [Dependency Exception](dependency-exceptions.md)
* [Colliding Data Types](colliding-datatypes.md)
* [Language Mismatch](language-mismatch.md)
* [Deployment Failed (with no error message)](deployment-failed.md)
* [Changes not being applied](changes-not-being-applied.md)

The most common Content [Transfer](../../deployment/content-transfer.md) / [Restore](../../deployment/restoring-content/README.md) issues are listed below:

* [Schema mismatch](schema-mismatches.md)
* [SQL Timeouts](../../../umbraco-deploy/deploy-settings.md#timeout-issues)
* [Dependency Exception](dependency-exceptions.md)
* [Media path too long](path-too-long-exception.md)

## Issues when using third-party packages

If you experience problems when using third-party packages on Umbraco Cloud there is a chance they are not compatible with Umbraco Cloud. Packages that add custom editors will need a Value Connector set up to work with Umbraco Deploy. Some of the most used packages out there have been included in the Community driven Umbraco Deploy Contrib project. You can include the Contrib dll in your project to help with a lot of them.

To see a list of packages covered look [here](https://github.com/umbraco/Umbraco.Deploy.Contrib).