# Architectural Overview

SEcond md file.

## Tasks - Here's what is needed

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


## Overview

This section introduces.

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
    
!!! bugs
    This is a code issue.  
    
## Second SEction

### Subsections

xxx

### Subsections

xxxx

#### Level Deeper

xx

#### Four levels deep

## First Section

The next area elaborates.

`code sample here`

Name | Type | Description
-----|------|------------
id | `string` | The id of the clip.
sources | `Array` | An array of available [source formats][source format].
duration | `string` | The duration of the clip in seconds.
isProtected | `boolean` | Whether the clip is DRM protected.
subclipStart | `number` | The start time location in seconds, only present if clip is episode.
subclipEnd | `number` | The end time location in seconds, only present if clip is episode.
getUrlByPreference | `function` | A method than can be used to get one source URL according to an order of preferenced formats.  [Read more…][getUrlByPreference]
getAllSourceUrls | `function` | A method that can be used to retrieve URLs for all provided source formats. [Read more…][getAllSourceUrls]

## Code Samples
```java
<!-- Instructs AcceptSDK to load Thyron Extension --><string-arrayname="extensions_list"><item>ThyronExtension</item></string-array><!-- Adding this line will ensure that AcceptSDK uses PosMate terminal as 	CNPController --><item name="acceptsdk_terminal_type"type="string">thyron</item><!-- Adding this line will ensure that AcceptSDK uses Thyron terminal as 	Default extension --><item name="wl_default_terminal_type_use" type="string" translatable="false">thyronExtension</item>NOTE: SDK is using reflection to bind extension library to SDK


```

```javascript
code looks like this
```

```php
<?php

// Initialize Variables
// Location of the VAS-Live API
$apiHost = 'vas-live-mdp.glomex.com';

// Values for these variables are provided by glomex
$accessToken    = "your-live-token";
$propertyName   = "your-channel";
$clientSaltIndex= '02';
$clientSalt     = "02xyi5AeHahb4eek6jee6u";

// Customize these variables based on your environment
$proto = 'https';
$clientLocation = 'http://yourlivesite.com';

// Hard-code the protocol/DRM combination - 
$protocols is used in the geturls() call
$protocols      = array("dash:clear");
$isDrmContent   = false;
// Note: clear indicates that no DRM is to be used

// Additional Security Settings
$simulateProtocolForgery = false;
$secureDelivery = false;

```