<img src="assets/icon.svg" width="64" height="64" alt="">

# Impact Miami 2.0 Hackathon

Our team's repo for **Impact Miami 2.0**, an Agentic AI challenge.

> Choose one prompt, then build an AI agent that answers it.

- **Pick one track.** Every team builds for a single track.
- **Build an AI agent.** Not just an app: an agent that takes action for real people.
- **One rubric.** Every track is scored on the same rubric. Most points wins.

## Challenge tracks

### Track 01: Agents for Access

Lots of people are locked out of things they're entitled to because systems are confusing, expensive, or only built for certain people. Build a platform that makes something more accessible, whether that's information, services, opportunities, or tools.

### Track 02: Agents for Civic Life

Make local government, public info, and community action easier to understand and take part in. The goal is helping regular people have more of a voice.

### Track 03: Agents for Health and Wellbeing

Build a platform that supports physical or mental wellbeing in a safe, responsible way. Not replacing professionals, but helping people find, understand, and follow through on care.

## Our pick

- **Track:** _TBD_
- **Idea:** _TBD_
- **Team:** _TBD_

## How we work

All changes go through pull requests into `main`.

```sh
git clone https://github.com/sebastianappel12-ai/impact-miami-hackathon.git
cd impact-miami-hackathon

git switch -c <your-name>/<short-feature>   # e.g. alex/agent-tools
# ...make changes...
git add -A && git commit -m "Add agent tool calling"
git push -u origin HEAD
gh pr create --fill                          # or open the PR on GitHub
```

- Keep PRs small and merge often; long-lived branches cause painful conflicts late in the day.
- Pull `main` before starting new work: `git switch main && git pull`.
- Never commit secrets. Put API keys in `.env` (ignored by git) and add the variable name to `.env.example`.
