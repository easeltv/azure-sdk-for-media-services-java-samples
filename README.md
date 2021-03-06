# Microsoft Azure Java SDK for Media Services Samples
This repository contains the following samples showing how to use the [Azure Java SDK for Media Service](https://github.com/Azure/azure-sdk-for-java/tree/master/services/azure-media).

* **azure-media-dynamic-encryption-aes**: This sample is a console Java application that shows how to use AES-128 Dynamic Encryption and Key Delivery Service. It is based on the .NET sample explained in this ACOM article: [https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-aes128/](https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-aes128/).
* **azure-media-dynamic-encryption-playready**: This sample is a console Java application that shows how to use PlayReady Dynamic Encryption and License Delivery Service. It is based on the .NET sample explained in this ACOM article: [https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-drm/](https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-drm/).
* **azure-media-dynamic-encryption-playreadywidevine**: This sample is a console Java application that shows how to use PlayReady and Widevine (DRM) Dynamic Encryption and License Delivery Service. It is based on the .NET sample explained in this ACOM article: [https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-drm/](https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-with-drm/).
* **azure-media-dynamic-encryption-fairplay**: This sample is a console Java application that shows how to use Azure Media Services to stream your HLS content protected with FairPlay Streaming (FPS). It is based on the .NET sample explained in this ACOM article: [https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-hls-with-fairplay/](https://azure.microsoft.com/en-us/documentation/articles/media-services-protect-hls-with-fairplay/).
* **azure-media-scale-workflow**: This sample is a console Java application that shows how to scale Encoding Reserved Units and Streaming Endpoints.
* **azure-media-analytics-indexer**: This sample is a console Java application that shows how to use Azure Media Services to run a media analytics job with the _Azure Media Indexer_ processor. It is based on the .NET sample explained in this ACOM article: [https://azure.microsoft.com/en-us/documentation/articles/media-services-index-content/](https://azure.microsoft.com/en-us/documentation/articles/media-services-index-content/).

These samples rely on the [azure-media maven package v0.9.4](http://mvnrepository.com/artifact/com.microsoft.azure/azure-media/0.9.4).

```xml
<dependency>
  <groupId>com.microsoft.azure</groupId>
  <artifactId>azure-media</artifactId>
  <version>0.9.4</version>
</dependency>
```
