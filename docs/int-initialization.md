# Initialization

After you [set up AcceptSDK](int-setup.md) in your own iOS and Android projects, you can start to use the AcceptSDK public APIs, beginning with the initialization method. Before looking at the code though, you should understand how the Public Test environment works.

## Using the Public Test Environment

As part of the initialization, you must point the SDK to an *environment*. An environment essentially means a Switch Back-end, as described in the [mPOS Architecture](mpos-architecture.md) and the [Switch Back-end Reference](switch-reference.md). Eventually, you will point to the live/production environment of the merchant for which you are developing the payment acceptance app. However, during development, you can take advantage of the Public Test environment, which is provided by Wirecard. 

To use the Public Test Environment, obtain credentials (i.e. username/password) from your Wirecard representative as described in [Set up Public Test](setup-publictest.md). 

## The AcceptSDK Class

As shown in the code snippets below, the highest-level class in the object hierarchy for both platforms is the `AcceptSDK` class. 

## Code Snippets

Insert from GIST

```objective-c
// Import the SDK header
#import <Accept/Accept.h>

// The SDK is initialized as shared instance so can be accessed 
// from multiple View Controllers
AcceptSDK *sdk = [AcceptSDK sharedInstance]; 

// Set the SDK target environment - in this case Public Test
// and the username and password to authenticate to it
[sdk setupWithEnvironment:AcceptEnvironmentPublicTest 
                 username:@"yourUsername" 
                 password:@"yourPassword"];
```


