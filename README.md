# creator1x · Branding · 3K

A Codex skill for branding and art direction: **Content → Context → Creative**. It ties business facts to a visual system and checks that the identity survives inside the actual product.

Adapted from principles in a user-supplied Ukrainian branding video. See [source notes](references/video-principles.md) for timestamps, attribution limits and the distinction between observed guidance and authored workflow. The video and its undisclosed client questionnaire are not redistributed.

## Install

Copy this repository's skill files into your Codex user skills directory, preserving `SKILL.md`, `agents/` and `references/`. Current Codex documentation lists `~/.agents/skills/` for user skills; if your environment already discovers this skill elsewhere, update that existing copy rather than installing a duplicate. If changes do not appear, restart Codex. See [official skill documentation](https://learn.chatgpt.com/docs/build-skills).

Invoke `$branding-3k`, or use a branding/art-direction request matching the skill description. No packages, API keys or remote services are required by the skill.

## Persistent agent rule

When the user explicitly wants this method included in their agent's defaults, add the scoped [3K rule](references/agents-rule.md) to their chosen `AGENTS.md`, preserving existing instructions. It covers branding and substantial visual work while leaving narrow fixes in their agreed scope. Global guidance belongs in `~/.codex/AGENTS.md`; a new run/session loads the updated instruction chain. See [official AGENTS.md documentation](https://learn.chatgpt.com/docs/agent-configuration/agents-md).

The workflow records **Content → Context → Creative**, then connects product facts to concrete decisions in the entrance, interior and main interaction. Working notes stay outside the customer-facing product.

This is a personal adapted workflow, not an official OpenAI package or an endorsement by the video creator. It does not guarantee uniqueness, higher fees, or fewer revisions.
