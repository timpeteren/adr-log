# Use single tenant design

* Status: accepted
* Deciders: tim.peter.edstrom@gmail.com
* Date: 2023-01-20

## Context and Problem Statement

There are multiple ways of deploying AAD B2C, single-tenant or multi-tenant, depending on the given scenario.
Mostly, single-tenant designs are utilized, but when the CIAM will have global reach, this may not be sufficient.

## Considered Options

* Single-tenant
* Multi-tenant (funnel-based and region-based)

## Decision Outcome

Chosen option: "Single-tenant", because applications and resources are located in a single region as well as users, which also are regional.

## Links

* AAD B2C global identity framework - https://learn.microsoft.com/azure/active-directory-b2c/azure-ad-b2c-global-identity-solutions
