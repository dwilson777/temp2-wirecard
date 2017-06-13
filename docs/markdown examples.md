![](assets/wirecard-white-logo.png) 

# Welcome to the AcceptSDK Documentation
This is a quick prototype of the AcceptSDK Project Documentation.

## Key Information about this Documentation
### Purpose

### Intended Audience

### Scope

### Prerequisities

## Formatting Examples

### Special Callouts

!!! note
    This is a note.  
 
!!! tip
    This is a tip.
    
!!! hint
    This is a hint.
    
!!! warning
    This is a warning.

!!! danger
    This is when you can get in trouble.
### Code Samples

```java
AcceptSDK.startPayment();(...) // see section 3.5, to learn how to fill new payment with data// optional, usually required when using chip and PIN controllersAcceptSDK.preauthorizePayment(...);(...)OnRequestFinishedListener = new OnRequestFinishedListener<Payment>() {	@Override	publicvoid onRequestFinished(final final Payment result) 	{		if (apiResult.isSuccess()) {			//payment succeeded, result object can be processed now		} else {			//payment failed with error		}	}};AcceptSDK.sendPayment(paymentListener);
```
    
### Task Lists - Here's what is needed

* [ ] Set up Hardware
* [ ] Verify Prereqs
* [ ] Install XCode
* [ ] Build your Apps
    * [ ] Login Information
    * [ ] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Sed egestas felis quis elit dapibus, ac aliquet turpis mattis
    * [ ] Praesent sed risus massa
* [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
* [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi