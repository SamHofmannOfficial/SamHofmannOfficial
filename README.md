Hi, I'm Sam

I keep apps working when AI companies retire their models.

When OpenAI, Anthropic, Google or another provider shuts a model down, apps that still call it break or quietly change. I find those apps and send small, single-purpose pull requests that move them to the replacement.

**So far:** 20 fix PRs opened on Nov 6, 2026; 8 merged so far.

**Coming up**

- **Nov 30, 2026:** Anthropic retires `claude-sonnet-4-5`
- **Dec 11, 2026:** OpenAI shuts down `gpt-5`, `gpt-5-mini`, `gpt-5-nano`, `gpt-5-pro`, `o3` and `o3-pro`
- **Jan 14, 2027:** OpenAI retires its GPT-4o and GPT-4.1 snapshots

**Need it done in your own code?** I'll move one repo to the replacement model, handle the parts that change (sampling settings, reasoning, tool calls, reading the response), and open a PR your team can review and test. From $400 for one repo, paid after you've reviewed it. Email Samhof10@gmail.com .

**Recent merged fixes**

- [mnemo-cortex #25](https://github.com/GuyMannDude/mnemo-cortex/pull/25): Claude Sonnet 4.5 to Sonnet 5.5, including reading text after thinking blocks
- [interview-coder-cn #2](https://github.com/YangHeng66/interview-coder-cn/pull/2): gpt-5-mini to gpt-5.6-terra, merged in under 2 hours
- [swarm-map #292](https://github.com/cyborg-garden/swarm-map/pull/292): new-agent default off Sonnet 4.5
- [Juggler #205](https://github.com/juggler-ai/juggler/pull/205): gpt-5-mini to gpt-5.6-luna
