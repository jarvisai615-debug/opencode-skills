# OpenCode skills catalog

An HTTP skills catalog for [OpenCode](https://opencode.ai): add the URL to your config and the skill is
available to your agent.

```jsonc
// opencode.jsonc
{
  "skills": ["https://raw.githubusercontent.com/jarvisai615-debug/opencode-skills/main/"]
}
```

## What is in it

| skill | the mistake it prevents |
|---|---|
| `make-a-test-hermetic-by-redirecting-its-writes` | a test that writes into the repo it is testing, so it passes or dirties the tree depending on what ran before |

Each skill is written from a real failure, and says what it cost to learn.
