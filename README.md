# Raven Cloud

A Push Notification Relay Server for [Raven](https://github.com/The-Commit-Company/raven) - built on the Frappe Framework.

## Overview

Raven Cloud acts as a centralized relay server that handles push notifications for multiple Raven instances. It uses Firebase Cloud Messaging (FCM) internally to deliver notifications to web and mobile clients.

Eventually, Raven Cloud can be extended for other features like Typesense search, Video calling and Raven's Marketplace.

## License

AGPL-3.0

## Dinext maintained references

The maintained line of this fork is `dinext/main/develop`. Selected vendor snapshots use `dinext/vendor/<line>`; company task branches use `dinext/feature/<task>`, `dinext/fix/*` or `dinext/upgrade/*`. Upstream branch names elsewhere in this README describe the original project. For Dinext work, use origin `https://github.com/Dinext-pro/raven_cloud.git` and the maintained Dinext line. Contributors may use their own branch names in external forks.

Future authorized release tags use `dinext/<upstream-tag>` or `dinext/<upstream-tag>-dinext.N`; application and upstream versions are unchanged. Existing published tags remain immutable. This reference-name transition enables no deployment, publishing or automatic upstream synchronization.
