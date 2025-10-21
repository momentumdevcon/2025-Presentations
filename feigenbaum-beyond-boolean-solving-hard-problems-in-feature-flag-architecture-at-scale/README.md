# Beyond Boolean: Solving Hard Problems in Feature Flag Architecture at Scale

**Speaker:** Ryan Feigenbaum

## Abstract

As feature flags move from simple toggles to core infrastructure, engineers face complex technical challenges that aren't covered in basic tutorials. This technical session dives deep into 3 critical problems in feature flag architecture at scale: maintaining consistency across regional deployments, handling circular dependencies between flags, and managing flag evaluation performance under heavy load.

The presentation walks through specific architectural patterns, including:

* Implementing consistent hashing for user targeting across distributed services
* Using dependency graphs to detect and prevent circular feature flag references
* Building efficient caching layers that handle rapid flag updates without sacrificing evaluation performance
* Managing flag cleanup through automated detection of stale references

Each pattern will be demonstrated with code examples showing both naive implementations and production-ready solutions. 

**Note:** The speaker has not uploaded any slides or resources.
