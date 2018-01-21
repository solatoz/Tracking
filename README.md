# Tracking
UPS Developer Kit

Tracking
The Tracking API allows applications to access UPS tracking information and query UPS to determine up-to-the-minute status of a shipment, including its delivery status and the time and location of the latest transit scan.

Tracking API components include:

Package or Shipment Tracking: Enables applications to provide tracking information based on a tracking number, shipment identification number, or reference number for packages, shipments or Mail Innovations pieces. A shipment may be a single transaction with multiple packages, or it may be a single freight shipment.
Tracking Numbers: Enables applications to track, locate, and verify arrival of packages and shipments.
Shipment Identification Numbers: Enables applications to use shipment identification numbers to identify and track every shipment as it moves through the UPS system.
Reference Numbers: Allows for flexibility. Applications can track any UPS package or shipment by a convenient, user determined reference number. Applications can assign a reference number to:
an individual package
all packages in a shipment
a single LTL shipment
an air or ocean freight shipment
PRO Numbers and Air Waybill Numbers: Enables applications to use PRO or Air Waybill numbers to identify and trace a freight shipment as it moves through the UPS system. A successful query by PRO or Air Waybill number returns all commodities within a shipment.
Candidate Bookmarks: Enables applications to distinguish between like references. In cases where more than one shipment matches a reference number, UPS returns identifying information about each shipment, and it marks each shipment with a unique candidate bookmark.
Prior to downloading this API you should be familiar with:

Programming URL or socket connections
Encoding and decoding XML documents
Designing and implementing a strategy into your existing software for handling errors
Available version(s): XML, Web Service, JSON 
Available mode(s): Package, LTL or Freight

Custom code that adapts your application´s business logic and data to the API must be developed in order to integrate this API´s functionality into your e-commerce applications.

To help you effectively integrate Tracking, the following guide and reference materials are included with the API:

Developer's Guide (with technical FAQs)
UPS logos and banners
Code samples:
DOTNET in C#
Java
Perl
PHP
XML
