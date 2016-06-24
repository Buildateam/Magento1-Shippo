Shippo Rates at the Checkout
Discounted Shipping Rates at the Checkout (Shippo)
OFFER CHEAP SHIPPING RATES TO YOUR CUSTOMERS AT THE CHECKOUT. POWERED BY SHIPPO.
Official Website for shipping API and shipping dashboard: https://goshippo.com/
Increase customer conversion rate by offering cheaper shipping rates! This extension connects your Magento store checkout to your https://goshippo.com/ account and gets discounted shipping rates for your customers.  This extension provides additional functionality and DOES NOT replace the official extension by Shippo. https://www.magentocommerce.com/magento-connect/shippo.html (You need to install it as well)
Highlights: 
Display and Charge Discounted Shippo rates during the Checkout
Add Handling and Shipping to Shippo Rates
Admin UI:
“Shippo” under System > Configuration > Sales > Shipping Methods > Shippo
NOTE THAT OFFICIAL SHIPPO EXTENSION IS UNDER Sales -> Shippo. http://screencast.com/t/voYdoZ0Z
Settings: 
  Enabled for Checkout: On/Off
  Private Auth Token: Shippo Token for getting rates.
  From *:  Address of the Shipment Origin.
  Weight Unit:  (lb / kg)
  Dimensions Unit: (in / cm) 
  ShipToApplicableCountries / ShipToSpecificCountries:  (What Countries to show Shippo Rates to)
New REQUIRED Attribute:  dimensions_lwh:
Upon installing the extension you will see a new attribute: ‘dimensions_lwh’. Shippo needs it in order to provide rates.
http://screencast.com/t/doysu8d2
http://screencast.com/t/xyTAgiji9
This field has validation: http://screencast.com/t/7JceXOFQ

Installation Steps:
1)Enter correct  Private Auth Token here:  System > Configuration > Sales > ShippingMethods > Shippo > Private Auth Token.
You can get it here:  http://screencast.com/t/lAV7Jrw9lS7
2) Enter correct FromAddress here:  System > Configuration > Sales > ShippingMethods > Shippo
3) Add Weight и Dimensions Attribute to Attribute Sets
4. Add Weight and Dimensions to products.
If the steps are followed correctly you will see Shippo rates at the checkout:
http://screencast.com/t/YbmmSNpdR3
If any of the steps aren’t followed correctly - the rates won’t appear.
If you are developer, all errors collected during requesting Shippo rates are logged here: /var/log/buildateam_shippo.log

Additional Information:
The rates are calculated the following way:
 1) The sum of the weights of all products in the cart are sent to Shippo.
 2) The dimensions are combined in such a way that the package takes the least possible size. Ex: If there are 2 products in the cart with the following dimensions: 10x6x4 and  10x5x3, the algorithm for dimensions will request a price for dimensions 10x6x7.

INFORMATION ABOUT SHIPPO:
Create discounted shipping labels fast. USPS Priority Mail and international prices are up to 80% off!!
Save up to $6 on every USPS Priority Mail shipping label!
Print a shipping label in seconds!
Access multiple carriers: USPS, Canada Post, FedEx, UPS, DHL Express and more
Shippo is the perfect shipping app for you whether you're shipping a few thousand packages a week or just a couple of packages a week. We support companies of all shapes and sizes.
--We have the BEST discounts on USPS Priority Mail shipping, hands down.
--Sign up is FREE!
--No monthly subscription fees
--Just $0.05 per shipping label
