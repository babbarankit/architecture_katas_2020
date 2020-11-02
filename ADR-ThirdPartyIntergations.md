# Architecture Style (Architecture Decision Record)

## Title
Third Party Integration Style for Smart Fridge, Kiosk Point of Sales, Delivery Partners.

## Status
Accepted.

## Context
Should Intergations be done via Microkernerl Architecture or in Application Desigm.

## Decision
Since a distributed architecture has been decided and moreover most parterns have apis which can be easily be dealt at application design instead of architecture it has been decided to move the 

## Consequences
For every patrner onbaorded in system, application code will have to support it. Therefore while designing application  plugins application pattern must evolve to support this via TemplateDesignPattern. Confugrabilty is handeled completely at application layer.