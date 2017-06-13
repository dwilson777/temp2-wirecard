# Glossary  

## Glossary of Acronyms

**AID** - xxx

**CNP** – Chip and PIN

**DUKPT** – Derived Unique Key Per Transaction

**EFT** - Electronic Funds Transfer. **EMV** - Short for Europay, Mastercard, Visa, which is a global standard for credit cards that use chips to authenticate and secure chip-card transactions. Currently, EMV is managed by EMVCo which includes American Express, China UnionPay, Discover and others.

**ERP** – Enterprise Resource Planning.**FW** - Firmware

**HSM** - Hardware Security Module is a physical device that helps with the decryption of PIN and other card holder data. 

**IPSP** – model – signing up merchants – Internet Payment Service Provider

**mPOS** - mobile Point of Sale. Secure, innovative and convenient way to turn a mobile device into a card acceptance device. 

**MSR** – sale transaction type

**MFI** – Made for iPhone – Apple programme 
**PCI DSS** – Payment Card Industry Data Security Standard. 

**REST** – Representational State Transfer.

**SEPA** - xxx**UUID** – Unique User Identifier

## Glossary of Terminology

Alphabetical object/method reference.

### A

**Acquiring Platform** – This is the primary payment facilitation component in the overall payment processing architecture. The Acquiring Platform is operated by the **Acquirer** and handles the **interchange** with the **card schemes** so that, ultimately, the transaction is debited from the account of the Cardholder. For AcceptSDK, a **merchant** requires a contract with an Acquiring Platform so that they have an account through which to route transactions. Wirecard's **Payment & Risk** division provides its own Acquiring Platform with the Wirecard **Acquiring and Processing** unit.

**Acquirer** - Entities that collect card payments that have been accepted by merchants, and then agregrate and separate those payments and and forward them on to **Issuers** for processing. Also known as **Merchant Acquirers**. 

**Acquiring and Processing** - Unit of Wirecard that provides an **Acquiring Platform**.

**Alipay** – The largest mobile and online payment platform in the world, with 400 million users in China alone. AcceptSDK supports payments made through Alipay. 
### B

**back-end** - Refers to the new **Switch** mPOS back-end. With AcceptSDK, the front-end payment acceptance app that you create is the front-end and Switch is the back-end. However, the Switch back-end itself forwards transactions on to the **Gateway**, which in turn, forwards the transaction on to the **Acquirer** and, ultimately, to the **Issuer** so that the consumer's payment is debited to their account.

**basket** - xxx

### C

**cardholder** - xxx

**card reader** - See **terminal**.

**cash register** - Wirecard 

**cashier** - xxx

**Chip and PIN cards** - See **EMV cards**.

**Chip and Signature cards** - See **EMV cards**.

**consumer** - User of a credit card. See **cardholder**. 

**contact cards** – xxx**contactless cards** – xxx

### D

### E

**electronic payments** - Same as cashless payments.

**EMV Cards** – smart cards, chip cards, IC cards – include magnetic stripes for backward compatibility; includes contactless cards – read over a short distance with RFID; EMV-compliant cards often called Chip and PIN or Chip and Signature cards

### F

**Firmware** – terminals; permanent software in read-only memory

**front-end** - use it?
### G

**Gateway** - Wirecard component that is responsible for the initial processing of the transaction and then routing to the **Acquirer**. Initial processing includes handling the secure decryption of **MagStripe**, **EMV** and both offline and online PIN transactions. An **HSM** is hosted to support decryption of card holder data. The Gateway is fully PCI DSS certified. For our partners developing with the AcceptSDK, there is a **Test Gateway** to help with initial development and testing. It allows you to simulate the full end-to-end payment process during development.

**gift card** – Type of payment.

### H

### I

**interchange** - Card scheme interaction.

**initialization** - For both the iOS and Android portions of the AcceptSDK, the first step in using the AcceptSDK is initialization. 

**IPSP** – model – signing up merchants – Internet Payment Service Provider

**Issuing Bank** - See **Issuer**.

**Issuer** - Also known as **Card Issuers**.

### J

### K

### L

### M

**Magstripe** - xxx

**MFI** – Made for I – Apple programme 

**merchant** - xxx

**Merchant Acquirers** - xxx

**mobile device** – Hardware on which apps created with the AcceptSDK run. Currently, iOS and Android devices are supported. 

**mobile Point of Sale (mPOS)** - xxx

**mPOS Portal** - Still exist with Switch. 

### N

### O

**offline PIN transactions** - xxx

**online PIN transactions** - xxx

**Objective-C** - xxx

**Online PIN vs. Offline PIN** – difference??

### P

**partner** - Refers to companies that collaborate with Wirecard and use the AcceptSDK to create payment acceptance apps for merchants.

**partner team** - The group of people at a partner company responsible for creating a payment acceptance app using the AcceptSDK. Typically, a partner team consists of a project manager and one or more developers. This AcceptSDK documentation is for the partner team. 

**pay in / pay out** – cash put in on out of cash register

**payment** – app or application?? Net result – on App Store or Google Play

**payment gateway** - See **Gateway**.

**payment method** - xxx

**Payment & Risk** - Division of Wirecard that handles **Acquiring and Processing** services. 

**payment acceptance app** - App that **partners** create with the AcceptSDK. This may be a fully-standalone app or it could be sub-component of a larger app. For example, a logistics company would already have an app that handles logistics such as deliveries, storage and so forth, but they may want to add payment acceptance functionality to it. So in this case the AcceptSDK would be used to create a sub-component of the logistics app. For simplicity though, the app created with the AcceptSDK is always referred to as the payment acceptance app. Once the payment acceptance app is created, the app will be used by **merchants** because it enables them to accept **electronic payments** on iOS and Android devices from **cardholders** and other **consumers**.  **payment gateway** – Transaction processing and routing. See **Gateway**. 

**Public Test** – environment for testing

**purchase** - The most common type of **sale transaction**, which involves the **consumer** buying something from the **merchant**. 

### Q

### R

**return** - 

### S

**sale** - xxx

**sale transaction** – one or more payment methods used for the sale; aka sale payment methods; 

**SEPA** – The Single Euro Payments Area (SEPA) is a payment-integration initiative of the European Union for simplification of bank transfers denominated in euro.

**Shift** – necessary to open and close; close after over

**Shift Activity** – cash in and out – cash operations**Swagger** – the original name for the openAPI specification – visualizing RESTful web services 

**Swift** - xxx

**Switch** - Intermediary proxy between the AcceptSDK front-end app and the Wirecard Gateway. For this reason, it is considered the back-end for the AcceptSDK front-end. See **mPOS Portal**. 

### T

**terminal** – problematic – payment terminal – mPOS terminal – card reader?

### U

**user** - xxx vs. merchant

### V

**vendor** – terminal vendors for cashless acceptance 

### Z

**Z-report** – Shift report; only for closed shifts 
