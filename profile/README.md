# The Rad Pack Way

## Overview

This is the beginning of something new. We're assembling a crew that can work independently of the core Statamic team to build and maintain Addons and Starter Kits that serve the community. Think of this as "second-party" — third-party Addons and Kits with a first-party guarantee that they will be built and documented to the Core Team's standards, well-maintained, and not abandoned.

## Most Rad Pack Addons Should be Free

The goal is provide broad usefulness for our users, not to make money. However, [some addons](https://statamic.com/addons/rad-pack/shopify) might require significant ongoing maintainence and may warrant being a paid product whose revenue would be shared with the developers.

## Go-Wide-But-Not-Too-Wide

Addons should have a reasonably wide appeal, but cover a feature, integration, or opinionated implementation that wouldn't be used by 80% or more of our users. It's okay to guess wildly about how many people would use something. We sure do. 

**Good Example** — 
A Mailchimp integration is a great Rad Pack Addon because lots of people use Mailchimp, but nowhere near 80%. Therefore, it would not be a good candidate for a Core Feature as it just doesn't make sense to ship updates to Statamic just to make a Mailchimp fix. 

**Bad Example** — 
A button that inserts table markup for the Markdown fieldtype would be a bad Addon, but a good Core Feature as anyone using the Markdown fieldtype might benefit from an easy shortcut that taps into feature that already exists.

## Ensure a Consistent Experience

"Like" Addons should have a "like" user experience. For example, Addons that integrate Mailchimp vs CampaignMonitor should _feel_ interchangable to the end user, even if they're very different under the hood. The names of settings should follow the same naming conventions, like `MAILCHIMP_API_KEY` and `CAMPAIGNMONITOR_API_KEY`. Any CP features or UI elements should be replecated if relevant. Language should be the same, calls to action the same, and documentation follow the same structure and flow. 

Exception: it's okay to use the lingo of a third party service if creates a better user experience. For example, `key` vs `token` vs `secret` — use what the service uses to reduce confusion.

## Regarding Take Overs

Addons being "taken over" or "absorbed" by the Rad Pack are subject to a major version bump in order to conform to these types of standards. We'll do our best to communicate these changes to existing users. If the addon is paid, it will become free in this major version bump.

## Wrappers Are Cool

It's fine if an Addon is mostly a wrapper around another package, as long as it adds value and makes the user experience simpler without any negatives or downsides. Don't skip wiring up parameters or arguments because _you_ don't need them. Someone else very well may.

## Take It Easy With Dependences

Keep dependencies to a minimum to keep required maintenance to a minimum. If you need a dependency, be sure to vet the most widely adopted and well maintained version. The exception is [Spatie](https://github.com/spatie) packages. Go nuts. They're awesome.
