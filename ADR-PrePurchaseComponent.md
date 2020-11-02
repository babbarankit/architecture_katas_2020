# Architecture Style (Architecture Decision Record)

## Title
Merging Cart and Promo in Seperate Component from Purchase Component.

## Status
Rejected.

## Context
Scope of Purchase Component.

## Decision
Cart and Order are closely coupled concepts. And Promo will also effect the Payments therefore the coupling is unavoidable.

## Consequences
Purchase Component will require multiple instances to support the elasticity.