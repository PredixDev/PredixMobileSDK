# PredixSDKforHybrid

The Predix SDK for Hybrid is a comprehensive suite of tools, frameworks and source examples that will enable and educate you on building mobile applications for the Industrial Internet of Things (IIoT). To get started, follow this documentation:
* [Get Started with the Predix Sync and SDKs](https://docs.predix.io/en-US/content/service/mobile/predix_sync/get-started-with-the-predix-sync-and-sdks) 
* [Running the Predix Mobile Sample App](https://docs.predix.io/en-US/content/service/mobile/predix_sync/running-the-mobile-sample-app)
* [Creating a Mobile Hello World Web App](https://docs.predix.io/en-US/content/service/mobile/predix_sync/creating-a-mobile-hello-world-web-app) 

Then, come back to this site to find all of the tools and examples to follow along.

## Predix Mobile App Container
The SDK for Hybrid includes Predix Mobile Reference App Containers for iOS and macOS.  The Mobile Reference App Container is a platform-specific environment in which Predix mobile applications are run. 
* For Android, you build the [Predix Mobile Reference App Container for Android](https://github.com/PredixDev/PredixMobileAndroidSampleApplication). 
* For iOS, you build the [Predix Mobile Reference App Container for iOS](https://github.com/PredixDev/PredixMobileiOS).
* For Mac, you build the [Predix Mobile Reference App Container for macOS](https://github.com/PredixDev/PredixMobileMacOS).


## pm CLI
The [Predix Mobile pm command line tool](https://github.com/PredixDev/predix-mobile-cli) allows you to manage your Predix Mobile apps and your mobile backend processes. It includes a set of commands that are invoked through the pm command line interface. These tools depend on both the Cloud Foundry and UAAC command line tools, so make sure they are installed and properly configured prior to installing the pm tool. 

## Predix Mobile Sync Gateway API
* https://developer.couchbase.com/documentation/mobile/current/references/sync-gateway/rest-api/index.html?language=ios#api-explorer

## Predix Mobile Client Core Services Framework
The Predix SDK for Hybrid provides several services as REST APIs to provide functionality to hybrid or native Mobile applications. The Client SDK consuming application, the Predix Mobile App Container, can interact with these local services following this general URL structure: http://pmapi//<parameters>.
The Predix Mobile App Container interprets URL requests and delegates them to the services in the Predix Mobile Client Core Services framework , which respond with a JSON payload describing the result of the call. 

## Additional Information
For additional technical documentation see the [Wiki](../../wiki) in this repo.

For native Swift and Java documentation specific to the iOS/macOS, Java and Android SDKs see the [code documentation site](http://predixdev.github.io/PredixMobileSDK/)

## Examples

The following examples show different ways you can use the Predix SDK for Hybrid. They are not meant for production use.

1. WEB-APPs
  * Predix Mobile Sample app - [MobileExample-WebApp-Sample](https://github.com/PredixDev/MobileExample-WebApp-Sample)  
  * Offline Authentication app - [MobileExample-WebApp-OfflineAuthentication](https://github.com/PredixDev/MobileExample-WebApp-OfflineAuthentication)  
  * Send Command app - [MobileExample-WebApp-SendCommand](https://github.com/PredixDev/MobileExample-WebApp-SendCommand)  
 
2. Microservices
  * Sample Command Processor - [MobileExample-Microservice-CommandProcessor](https://github.com/PredixDev/MobileExample-Microservice-CommandProcessor)  
  * Sample Sync Processor that communicates with Predix Asset service - [MobileExample-Microservice-AssetIntegration](https://github.com/PredixDev/MobileExample-Microservice-AssetIntegration)  

  
3. Android Client Examples
 * Sample hybrid application - [PredixMobileAndroidSampleApplication](https://github.com/PredixDev/PredixMobileAndroidSampleApplication)

4. Java Client Examples
 * Sample hybrid application using JavaFX - [PredixMobileJavaSampleApplication](https://github.com/PredixDev/PredixMobileJavaSampleApplication)
 
