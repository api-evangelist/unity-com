# Unity (unity-com)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Unity is a real-time 3D content creation platform — the Unity engine powers cross-platform games, simulations, XR experiences, and digital twins, while Unity Gaming Services (UGS) and Unity Cloud provide a production backend for live games and 3D pipelines. UGS exposes a coherent set of 30+ REST APIs at `services.api.unity.com` covering authentication, cloud save, cloud code, economy, leaderboards, remote config, relay, lobby, matchmaker, game-server hosting (Multiplay), voice/text chat (Vivox), friends, analytics, triggers, scheduler, content delivery, monetization/LevelPlay, asset management, and organization administration. Unity also ships open-source frameworks including ML-Agents, Netcode for GameObjects, and the Input System, and hosts the canonical Unity C# reference source on GitHub.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/unity-com/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Real-Time 3D, Game Engine, Gaming, Multiplayer, Cloud, Live Operations, Digital Twins, XR, ML-Agents, Asset Pipeline

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Plans (2026)

| Plan | Annual / Seat | Monthly / Seat | Notes |
|---|---|---|---|
| Personal | Free | Free | Orgs under $200K annual revenue/funding |
| Pro | $2,310 | $210 | 5% increase effective 12 Jan 2026; Havok Physics no longer bundled |
| Enterprise | Custom (~$4K–$5K+/seat) | — | Source-code access, Premier support |
| Industry | Custom | — | Pixyz, CAD ingest, digital-twin tooling |

## APIs

### Unity Authentication API
Player Authentication for Unity Gaming Services — anonymous, social, username/password, and custom-ID sign-in. Mints the player JWT consumed by every other UGS service.

**Human URL:** [https://services.docs.unity.com/auth/v2/](https://services.docs.unity.com/auth/v2/)

- [Documentation](https://services.docs.unity.com/auth/v2/)
- [Documentation — Player Authentication REST API](https://docs.unity.com/ugs/en-us/manual/authentication/manual/rest-api)

### Unity Cloud Save API
Per-player and per-game-session key/value persistence with versioning and conflict resolution.

**Human URL:** [https://services.docs.unity.com/cloud-save/v1/](https://services.docs.unity.com/cloud-save/v1/)

- [Documentation — Player Data](https://services.docs.unity.com/cloud-save/v1/)
- [Documentation — Admin](https://services.docs.unity.com/cloud-save-admin/v1/)
- [Documentation — REST API Tutorial](https://docs.unity.com/ugs/en-us/manual/cloud-save/manual/tutorials/rest-api)

### Unity Cloud Code API
Server-authoritative JavaScript scripts and C# modules at $0.072/compute-hour.

**Human URL:** [https://services.docs.unity.com/cloud-code/v1/](https://services.docs.unity.com/cloud-code/v1/)

- [Documentation — Runtime](https://services.docs.unity.com/cloud-code/v1/)
- [Documentation — Admin](https://services.docs.unity.com/cloud-code-admin/v1/)

### Unity Economy API
Server-authoritative currencies, inventory items, virtual purchases, and real-money purchases with balances and transaction history.

**Human URL:** [https://services.docs.unity.com/economy-admin/v2/](https://services.docs.unity.com/economy-admin/v2/)

### Unity Leaderboards API
Bucketed, partitioned, and tiered scoring strategies with reset schedules and paginated rankings.

**Human URL:** [https://services.docs.unity.com/leaderboards-admin/v1/](https://services.docs.unity.com/leaderboards-admin/v1/)

### Unity Remote Config API
Feature flags, balance values, and game settings — segmented by audiences and staged across environments.

**Human URL:** [https://services.docs.unity.com/remote-config-admin/v1/](https://services.docs.unity.com/remote-config-admin/v1/)

### Unity Relay API
NAT-traversal relay for peer-to-peer multiplayer with encrypted DTLS connections and global regions.

**Human URL:** [https://services.docs.unity.com/relay-allocations/v1/](https://services.docs.unity.com/relay-allocations/v1/)

### Unity Lobby API
Create, list, join, and manage multiplayer lobbies with metadata, host migration, and Relay/Multiplay integration.

**Human URL:** [https://services.docs.unity.com/guides/ugs-cli/latest/lobby/Lobby%20Command%20Line/overview/](https://services.docs.unity.com/guides/ugs-cli/latest/lobby/Lobby%20Command%20Line/overview/)

### Unity Matchmaker API
Rule-based matchmaking on skill, latency, party, and custom attributes; pairs with Multiplay or Relay.

**Human URL:** [https://services.docs.unity.com/matchmaker-admin/v3/](https://services.docs.unity.com/matchmaker-admin/v3/)

### Unity Multiplay (Game Server Hosting) API
Global dedicated server fleets, builds, machines, allocations, and queues. Note: Unity ended direct Multiplay operations 31 March 2026 — service is now operated by Rocket Science Group.

**Human URL:** [https://services.docs.unity.com/multiplay-config/v1/](https://services.docs.unity.com/multiplay-config/v1/)

- [Pricing](https://docs.unity.com/ugs/en-us/manual/game-server-hosting/manual/concepts/pricing)

### Unity Vivox Voice and Text Chat API
In-game voice and text chat with moderation, channel management, and compliance evidence.

**Human URL:** [https://services.docs.unity.com/moderation/v1/](https://services.docs.unity.com/moderation/v1/)

### Unity Friends API
Friends, blocks, invitations, and presence — cross-platform.

**Human URL:** [https://services.docs.unity.com/friends/v1/](https://services.docs.unity.com/friends/v1/)

### Unity Analytics API
Standard and custom event ingest with funnels, retention, monetization, and segmentation reporting.

**Human URL:** [https://services.docs.unity.com/analytics/v1/](https://services.docs.unity.com/analytics/v1/)

### Unity Triggers API
Event-driven Cloud Code execution in response to UGS service events.

**Human URL:** [https://services.docs.unity.com/triggers-admin/v1/](https://services.docs.unity.com/triggers-admin/v1/)

### Unity Scheduler API
One-shot and recurring Cloud Code jobs with timezone awareness and retries.

**Human URL:** [https://services.docs.unity.com/scheduler-admin/v1/](https://services.docs.unity.com/scheduler-admin/v1/)

### Unity Content Delivery API
Versioned asset/bundle distribution — buckets, badges, releases, and signed asset URLs.

**Human URL:** [https://services.docs.unity.com/content-delivery-management/v1/](https://services.docs.unity.com/content-delivery-management/v1/)

- [Documentation — Client](https://services.docs.unity.com/content-delivery-client/v1/)

### Unity Monetize and Ads API
Mediation, user-acquisition campaigns, and statistics for Unity's ad surface (formerly ironSource / LevelPlay).

**Human URL:** [https://services.docs.unity.com/monetize/v1/](https://services.docs.unity.com/monetize/v1/)

- [Documentation — Advertise](https://services.docs.unity.com/advertise/v1/)
- [Documentation — Statistics](https://services.docs.unity.com/statistics/v2/)

### Unity Asset Manager API
Digital asset management for 3D, image, audio, and animation assets across game and Industry workflows.

**Human URL:** [https://services.docs.unity.com/assets-manager/v1/](https://services.docs.unity.com/assets-manager/v1/)

### Unity Admin and Identity (SCIM, Access, Core) API
Organizations, projects, environments, resource policies, and SCIM 2.0 identity provisioning.

**Human URL:** [https://services.docs.unity.com/unity/v1/](https://services.docs.unity.com/unity/v1/)

- [Documentation — Access](https://services.docs.unity.com/access/v1/)
- [Documentation — SCIM](https://services.docs.unity.com/scim/v2/)
- [Documentation — Releases](https://services.docs.unity.com/release/v1/)

## Common Resources

- [Portal](https://unity.com)
- [Portal — Unity Cloud](https://cloud.unity.com)
- [Portal — Unity Dashboard](https://dashboard.unity.com)
- [Unity Engine Manual](https://docs.unity3d.com/Manual/index.html)
- [Unity Scripting API Reference (C#)](https://docs.unity3d.com/ScriptReference/index.html)
- [Unity Gaming Services Manual](https://docs.unity.com/ugs/en-us/manual)
- [Unity Services Web API Docs](https://services.docs.unity.com/)
- [Unity Cloud](https://docs.unity.com/cloud)
- [Unity Learn](https://learn.unity.com)
- [Discussions](https://discussions.unity.com)
- [Support](https://support.unity.com)
- [Status](https://status.unity.com)
- [Releases / Changelog](https://unity.com/releases)
- [Terms of Service](https://unity.com/legal/terms-of-service)
- [Privacy Policy](https://unity.com/legal/privacy-policy)
- [Security / Trust](https://unity.com/security)
- [Sign Up — Unity ID](https://id.unity.com)
- [Sign Up — Dashboard](https://dashboard.unity.com)
- [Blog](https://unity.com/blog)
- [Blog (alt)](https://blog.unity.com)
- [GitHub Organization — Unity-Technologies](https://github.com/Unity-Technologies)
- [SDK — ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents)
- [SDK — Netcode for GameObjects](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects)
- [SDK — Input System](https://github.com/Unity-Technologies/InputSystem)
- [SDK — Unity C# Reference Source](https://github.com/Unity-Technologies/UnityCsReference)
- [Samples — Entity Component System](https://github.com/Unity-Technologies/EntityComponentSystemSamples)
- [Samples — AR Foundation](https://github.com/Unity-Technologies/arfoundation-samples)
- [Samples — Multiplayer Co-Op](https://github.com/Unity-Technologies/com.unity.multiplayer.samples.coop)
- [CLI — Unity Gaming Services CLI (UGS CLI)](https://docs.unity.com/ugs-overview/manual/ugs-cli/install)
- [Portal — Unity Gaming Services](https://unity.com/products/gaming-services)
- [Pricing — UGS](https://unity.com/products/gaming-services/pricing)
- [Pricing — 2026 Updates](https://unity.com/products/pricing-updates)
- [Plans](plans/unity-plans-pricing.yml)
- [Rate Limits](rate-limits/unity-rate-limits.yml)
- [FinOps](finops/unity-finops.yml)

## Maintainers

- **Name:** Kin Lane
- **Email:** info@apievangelist.com
- **X:** [@apievangelist](https://x.com/apievangelist)
- **URL:** [https://apievangelist.com](https://apievangelist.com)
