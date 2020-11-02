# Farmacy Food Architecture Katas

## Resources

1. [Architecture Toplogy Diagram](ArchitectureToplogy.jpg)

## Identifying Components

### Methodology
Team attempted the Worklow Method to identify components, but the approach failed to find the right granulaity and soon found that this leads to much depth leading to granuality of services.
Therefore the action/actors approach was adopted.

### Actors and Actions
Customer
KitchenVendor
SmartFridge
KioskRepresentative
DeliveryPartner
BusinessManager
System

### Identified Components

1. **Customer Management:** Manage all information related with Customer i.e. Profile, Health Cards, Health Goals, etc

1. **Food Catalogue:**  Manage Food Catalogue Items & Get Customer Food Catalogue (Subscription or Current Inventory).

1. **Purchase:**  Manage all purchase relate operations including Cart, Order, Payments, and Wallet (for Paybacks/Refunds etc). Delivery Packages from Kitchen to Kiosk/Smart Fridge can also act as System Generated Order so that the flow remain consistent for inventory and 

1. **Help Desk:** Manage Tickets and Feedbacks. 

1. **Recommendation Engine:** Find personalised Food Catalogue Items recommended for user. This will be connected to a recommendation engine which can be in future work on Big Data Analysis basis (eager or lazy mode).

1. **Promo Engine:** Promos can be created via user input.

1. **Kiosk Service:** Integrates with differenr Kiosks (Point of Sales API) via Template Method.

1. **Smart Fridge Service:** Integrates with differenr Kiosks (Point of Sales API) via Template Method.

1. **Inventory Forecast Engine:** Find Inventory Forecasts for upcoming days based on subscription and learning from history of on-spot sales (this configuration can be stored in Locations).

1. **Locations:** Manage Vendors, Kitchens, Smart Fridges, Kiosks.

1. **Delivery Component:** Coordinate with delivery services and OTP third party services. Generate and Verif OTPs.