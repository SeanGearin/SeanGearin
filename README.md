Indistinct

AI that holds what you know.

The intelligence layer is getting built by Anthropic, OpenAI, and Google. None of them will hold your world — the people, deals, decisions, and open threads that make your operation yours. Indistinct closes that gap: durable private context inside the AI you already use, that stays yours and goes where you go. Product-first, alongside a hands-on practice for family offices, founders, and chiefs of staff — wherever one person's leverage is worth everything.


Virgil

Indistinct's flagship. A persistent brain that works inside Claude and ChatGPT at once: talk naturally and it captures who's who and what's connected, writes it to a knowledge graph mid-conversation, and pulls the right context forward before the next ask. No new app, nothing to tag, nothing to manage — you just talk, and it keeps up.

Switch models whenever you want; your memory doesn't reset when you do. It isn't a feature locked inside someone else's product — it's the one part of your stack that's actually yours, and it can't be switched off, walled in, or left behind.

When facts change, the old record is superseded, never deleted — the brain keeps receipts. Ask it how it knows something and it tells you: source, date, confidence.

The graph-memory core is built on gbrain, Garry Tan's open-source engine, which Indistinct runs in production and extends. Multi-tenant isolation, measured formation, reconciliation, and the cross-model connector are ours, with fixes contributed back upstream. Every artifact is written to a private repository — the record is the customer's, fully auditable, built to leave with them.

The proof — under the hood, for the people who want to look

Every fact carries where it came from — what you actually said, or a clearly-marked inference, never a guess — and the day it landed. When something changes, the old version is superseded, not painted over, so the record stays current and traceable. It's a structured record your AI pulls the exact relevant piece from, not the wall of text most "AI memory" really is — and it's measured, not asserted: formation quality is benchmarked against N=92 operator-adjudicated cases, detection precision moving 88% → 97.1% across the last hardening cycle, every label carrying its provenance. The benchmark grows itself, production corrections landing as new labeled cases the moment they're made. All of it exportable anytime, in a format you keep.

Where it's going

Launch on the Claude Connectors Directory and the ChatGPT app store — both submitted, in review.
Standards-based brain export — your entire graph, downloadable, in a format any system can read.
A time axis no other AI memory has — what changed this month, what did I believe in March, what do I owe people and what's slipping.

The bet is simple: the model providers build the summary. Virgil builds the record.

The name

Chosen by Claude, given the problem it was built to solve. In Dante, Virgil is the guide through every layer of complexity below — but cannot enter Heaven. Reason takes you to the threshold. The decision past it is yours.
Virgil guides. You decide.

Stack

Cross-model by design — one brain, live inside both Claude and ChatGPT
Anthropic Claude — reasoning and synthesis
Graph-memory core — supersession chains, per-fact confidence, provenance; built on the open-source gbrain engine, extended for production
MCP connector — registered in Claude.ai, in review for the ChatGPT app store
Custom OAuth 2.0 authorization server with branded consent
Cloudflare Workers backend — edge-deployed, cron-driven, multi-tenant with strict isolation
GitHub persistent memory — every decision auditable
Composer workflow — rebuilds operating context on every change to the record
Managed sub-agents — parallel workstreams, adversarial review, cadence-based synthesis
Scheduled intelligence — morning briefs and field monitors before the day starts
Zero-server-inference economics — heavy reasoning rides the customer's own AI



indistinct.ai · virgilknows.com
