# SSDD Blinded Comparative Review

This public repository contains **only** the materials needed to complete a bounded, blinded engineering review of three unlabeled shared-state policy records.

It does **not** contain SSDD research source, PayLock source, Yaqeen source, raw gem5/SimCXL artifacts, Cherry infrastructure information, production configuration, credentials, customer data, or the A/B/C unblinding key.

## Why this review exists

In a bounded local 133-case contract, SSDD, a CAS/retry policy reference, and a single-writer-sequencer policy reference each met the declared containment and arrival-order semantics when the conventional references made their canonicalization policies explicit. There is no declared winner.

The review asks a narrower question: from a retained decision record, can an engineer determine the governing rule, material condition, prior valid checkpoint, and relevant policy surface clearly enough to audit a shared-state decision?

## Who should participate

This is intended for practitioners with experience in distributed systems, concurrency, shared-memory or memory-system architecture, chiplets/CXL, systems verification, reliability, incident analysis, or systems-runtime engineering. The task is not a popularity poll or product endorsement; it requires evaluating retry, ordering, integrity, and diagnostic-policy trade-offs.

## Self-service participation

1. Open [`reviewer-packets/README.md`](reviewer-packets/README.md).
2. Verify the packet with `sha256sum -c SHA256SUMS`.
3. Review all eighteen unlabeled records: six cases, each labelled `A`, `B`, and `C`.
4. Submit the fixed response through [New blinded review response](../../issues/new?template=blinded-review-response.md). No owner contact, invitation, or permission is required.

The label key is intentionally absent and will not be published until qualifying responses are locked. A response may find SSDD clearer, a baseline clearer, no material difference, or insufficient evidence.

## Public outreach copy

The exact LinkedIn post is available in [`LINKEDIN-POST-COPY.md`](LINKEDIN-POST-COPY.md). It directs reviewers only to this minimal public review repository.

## Scope limits

This is a local policy-reference review. It makes no claim about physical CXL, FPGA, silicon, latency, jitter, percentiles, throughput, scaling, production behavior, or universal superiority.

## Rights

Use of the packet is governed by [`COPYRIGHT-NOTICE.md`](COPYRIGHT-NOTICE.md). It grants only the narrow permission needed to inspect the packet and submit an independent review response; it does not grant rights in the underlying research or product materials.
