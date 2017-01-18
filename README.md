# Bikeshed

Please log issues to start with.

## Introduction

This is a reaction to https://m.reddit.com/r/rust/comments/5nu1w7/rust_and_the_limits_of_swarm_design/ and aims to provide something like https://github.com/kud1ing/awesome-rust for production/business users.

## Concept

As ESR points out, the rust community does not have a BDFL, this gives us the freedom to rally around issues as a community and evolve concepts/ideas as a swarm, without having to get someone's permission to tackle the issue. 

This GitHub organisation is one experiment to see if a community of production focused users and contributors can solve some of the problems laid out in the article. In broad strokes this might involve:

- Rallying a core group of production and business focused developers and companies to establish a forum for nomination, selection, incubation and maturation of crates and groups of crates (initiatives) useful for popular production workloads.

- Providing a high quality list of suggested crates to solve common tasks, at a high level crate categories could include: 
  
  - async/epoll
  - parsing
  - rpc
  - database
  - web frameworks
  - (lots more, clearly, feedback would be great)
  
- Categories could include a couple of suggestions such as: proven, up and coming, waning but widely used.

- Criteria for selection could include: the "bus factor", whether or not a crate has commercial support behind it, developer reputation, maintenance and activity, idiomatic usability (supports iterators, traits) of the api, license, documentation, clippy, CI integrated repo, use in other projects, etc.

- Assistance can also be provided to crate authors to help them improve the uptake of their crates.

- An API could be provided to crates.io for badges/ranking/listing purposes.

## Motivation

Having popular tasks/workloads within the stdlib is a mixed blessing, it assists with discoverability but can also lock in a paradigm that could eventually keep the language back as the community and userbase struggle to deprecate legacy thinking.

## Goals

Interview the business/production user community:

- Is this a viable idea?
- Should this be surfaced as something that aspiring Rustaceans can easily stumble across?
- What are the categories that would interest production developers?
- How should the information be presented?

## Inspiration

- Look at the areweXyet? sites.


