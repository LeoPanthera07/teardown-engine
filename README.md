# AI Product Teardown Engine

Reusable LLM prompt for dissecting AI products into 6 engineering layers (Data → Scale). Built Day 5: V1 prompt → 3-LLM comparison → V2 rebuild → stress-tested.

## Quick Start
1. Copy `system-prompt-v2.md` into Claude 3.5 Sonnet (Thinking mode).
2. User msg: "[PRODUCT]: Spotify Discover Weekly"
3. Get structured teardown w/ relevance ratings, challenges, skills.

## Why?
- Tests AI depth under hood (job interview staple).
- Multi-LLM process: Specificity ↑25% via extraction/few-shot.

## Files
- `system-prompt-v1.md`: Initial draft.
- `system-prompt-v2.md`: Production version (use this).
- `llm-comparison.md`: Scores (Claude wins).
- `best-parts-map.md` / `llm-selection.md`: Merge decisions.
- `final-teardown.md`: Netflix example.
- `stress-test.md`: Spotify validation.
- `reflection.md`: Learnings.

Example Output Snippet:
Layer 3 — Machine Learning Models
Relevance: High

text

Fork & run on your products (Zomato, Perplexity.ai).