---
stage: accepted
start-date:

teams: # list teams that are relevant
  - 

project-link:
---

<!---
Directions for above:

stage: Leave as is
start-date: Fill in with today's date, 2032-12-01
teams: Include only the for which this RFC applies
project-link: Leave as is
-->

<-- Replace "RFC title" with the title of your RFC -->
# RFC Title 

## Summary

> One paragraph explanation of the deprecation.

## Motivation

> Why are we doing this? What are the problems with the deprecated feature?
What is the replacement functionality?

## Transition Path

> This is the bulk of the RFC. Explain the use-cases that deprecated functionality
covers, and for each use-case, describe the transition path.
Describe it in enough detail for someone who uses the deprecated functionality
to understand, for someone to write the deprecation guide, and for someone
familiar with the implementation to implement.

> It can be helpful to write the deprecation guide as part of this section. Published deprecation
> guides can be found at https://deprecations.emberjs.com/.

> Please keep in mind any implications within the Ember ecosystem, such as:
> - Lint rules (ember-template-lint, eslint-plugin-ember) that should be added, modified or removed
> - Features that are replaced or made obsolete by this feature and should eventually be deprecated
> - Ember Inspector and debuggability
> - Server-side Rendering
> - Ember Engines
> - The Addon Ecosystem
> - IDE Support
> - Blueprints that should be added or modified

## How We Teach This

> Would the acceptance of this proposal mean the Ember guides must be
re-organized or altered? Does it change how Ember is taught to new users
at any level?
Does it mean we need to put effort into highlighting the replacement
functionality more? What should we do about documentation, in the guides
related to this feature?
How should this deprecation be introduced and explained to existing Ember
users?

> Keep in mind the variety of learning materials: API docs, guides, blog posts, tutorials, etc.

## Drawbacks

> Why should we *not* do this? Please consider the impact on teaching Ember,
on the integration of this feature with other existing and planned features,
on the impact of the API churn on existing apps, etc.
There are tradeoffs to choosing any path, please attempt to identify them here.

## Alternatives

> What other designs have been considered? What is the impact of not doing this?

## Unresolved questions

> Optional, but suggested for first drafts. What parts of the design are still
TBD?
