# Unity (unity-com)
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
