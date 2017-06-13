# Sale Overview
The objective of every merchant is to make sales so not unexpectedly the Sale API is probably the most important API in the AcceptSDK. 

## Supported Payment Methods

The AcceptSDK enables you to build functionality to process any of these payment methods used by consumers:

* Cash
* Card - credit or debit
* Alipay
* SEPA

## Passing Information to Sale Request

Every sale begins with a [Sale Request](int-salerequest.md). At minimum, you need to provide the following to the Sales Request:

* payment method (one of the four listed above)
* Individual Items that comprise the Sale with individual information for each:
 * 	Unit price
 * Currency
 * Tax Rate

 If the consumer chooses the Card payment method then you also need to indicate a Terminal. See [Set up Terminals](setup-terminals.md) for more information about terminals and how to set them up in a testing environment. Also, see [Terminal Discovery](int-terminaldiscovery.md) for complete information... 





