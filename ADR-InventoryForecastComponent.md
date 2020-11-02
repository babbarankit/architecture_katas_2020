# Inventory Forecast Engine (Architecture Decision Record)

## Title
Inventory Forecast Engine.

## Status
Accepted.

## Context
Handling Customer Subscription as first class requirement.

## Decision
To maximize profits at the Kiosk and Smart Fridges, we will like to support on-spot sales notmarking inventory item immediately on hold, it is valuable to support this. Moreover Kitchen Owners will like to predict total sales at alll sales points includiing application, and apart from some sales partern that can be configured in locations databse, subscriptions will also effect the cariable future inventory demands. Therefore this would simply overall logic.

## Consequences
Subscriptions will generate child orders.