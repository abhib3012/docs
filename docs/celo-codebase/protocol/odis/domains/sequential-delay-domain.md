---
title: Sequential Delay Domain
---
import PageRef from '@components/PageRef'

The Sequential Delay Domains is an [ODIS Domain](/celo-codebase/protocol/odis/domains) supporting signature-authenticated rate limits defined as a series of time-delayed stages.
The motivating use case is allowing wallets to define how often users can attempt to recover their account via the scheme outlined in [Pin/Password Encrypted Account Recovery](/celo-codebase/protocol/identity/encrypted-cloud-backup), but can be used in any other application that need an authenticated rate limit represented as a series of time delayed stages.

## Specification

A full specification of the Sequential Delay Domain is available in an extension to CIP-40.

<PageRef url="https://github.com/celo-org/celo-proposals/blob/master/CIPs/CIP-0040/sequentialDelayDomain.md" pageName="Sequential Delay Domain Specification" />
