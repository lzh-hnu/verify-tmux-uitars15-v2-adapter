# Verify tmux for UITARS15_v2: Action Grounding Adapter

A verification companion for grounding UITARS15_v2 terminal actions in tmux panes.

## Verification Focus

- Agent: UITARS15_v2
- Track: Adapter Verification
- Shared image: `docs/assets/hero.png`
- Image position: fixed in the right-side hero media container

## Trace Notes

- Action proposals include target pane context.
- Command acknowledgements are linked to visible output changes.
- Ambiguous focus changes are surfaced as verification warnings.

## Review Lens

- Target-pane precision
- Action acknowledgement
- Ambiguity reporting
