# PredixMobileSDK

The Predix Mobile SDK is a comprehensive suite of tools, frameworks and source examples that will enable and educate you on building mobile applications for the Industrial Internet of Things (IIoT). To get started, follow this documentation:
* [Get Started with the Mobile Service and Mobile SDK] (https://www.predix.io/docs#rae4EfJ6) 
* [Running the Predix Mobile Sample App] (https://www.predix.io/docs#EGUzWwcC)
* [Creating a Mobile Hello World Webapp] (https://www.predix.io/docs#DrBWuHkl), 

Then come back to this site to find all of the tools and examples to follow along.

##Predix Mobile Container
The [Predix Mobile container](https://github.com/PredixDev/PredixMobileReferenceApp) is a platform-specific environment in which Predix mobile applications are run. It contains the implementation of our Predix Core Services framework.

##pm CLI
The [pm CLI](https://github.com/PredixDev/predix-mobile-cli) is a Command Line Interface that facilitates the management of Predix mobile users, roles, Predix mobile applications and their constituent web app dependencies. You must install and configure the Cloud Foundry cf CLI and uaac CLI before installing the pm CLI.

## Additional Information
For additional technical documentation see the [Wiki](../../wiki) in this repo.

## Examples
1. WEB-APPs
  * [MobileExample-WebApp-Sample : The Sample App](https://github.com/PredixDev/MobileExample-WebApp-Sample)  
  * [MobileExample-WebApp-OfflineAuthentication : For offline authentication](https://github.com/PredixDev/MobileExample-WebApp-OfflineAuthentication)  
  * [MobileExample-WebApp-SendCommand : Sample webapp that sends a test command to Mobile Service and displays the response. example](https://github.com/PredixDev/MobileExample-WebApp-SendCommand)  
  * [MobileExample-WebApp-AssetIntegration : Asset integration webapp example](https://github.com/PredixDev/MobileExample-WebApp-AssetIntegration)  

2. Microservices
  * [MobileExample-Microservice-CommandProcessor : A sample command-processor example](https://github.com/PredixDev/MobileExample-Microservice-CommandProcessor)  
  * [MobileExample-Microservice-AssetIntegration : A sample sync-processor which communicates with Predix-Assets service](https://github.com/PredixDev/MobileExample-Microservice-AssetIntegration)  

3. iOS Client Services
  * [MobileExample-iOSService-Sample : Basic native iOS service example](https://github.com/PredixDev/MobileExample-iOSService-Sample)
  * [MobileExample-iOSService-SingleLocation : Retrieve user's current location in iOS via a service](https://github.com/PredixDev/MobileExample-iOSService-SingleLocation)
  * [MobileExample-iOSService-Barcode-Scanner : Barcode scanner implementation for iOS via native service](https://github.com/PredixDev/MobileExample-iOSService-Barcode-Scanner)
  * [MobileExample-iOSService-Camera : Camera service implementation for iOS via native service](https://github.com/PredixDev/MobileExample-iOSService-Camera)

4. iOS Client Examples
  * [MobileExample-iOS-StoreLogsInDatabase : Store logs in the database](https://github.com/PredixDev/MobileExample-iOS-StoreLogsInDatabase)
  * [MobileExample-iOS-NativeIssuesListApp : using the Predix Mobile SDK for iOS to create a non-hybrid, native iOS app](https://github.com/PredixDev/MobileExample-iOS-NativeIssuesListApp)
