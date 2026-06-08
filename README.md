# Pranjal Bhatia

I build around AI agents, devtools, and robotics/CAD.

The thread through most of my work is simple: I like systems that still make sense when they leave the demo. Agents need evals and failure recovery. Robotics needs latency, calibration, contact, and bad sensors to be treated as first class problems. Devtools need to save real time, not just look good in a screen recording.

Right now I am focused on:

- AI agents and MCP tooling
- devtools for testing, automation, and developer workflows
- robotics, CAD, simulation, and embodied AI
- meaningful OSS contributions instead of drive-by PRs

## Recent OSS work

Open PRs and patches I am actively tracking:

- [`gumyr/build123d`](https://github.com/gumyr/build123d/pull/1330): create planes from three points
- [`modelcontextprotocol/python-sdk`](https://github.com/modelcontextprotocol/python-sdk/pull/2734): preserve stdio streams in server transport
- [`CadQuery/cadquery`](https://github.com/CadQuery/cadquery/pull/2044): docs for Workplane tags and `end()` usage
- [`CadQuery/cadquery`](https://github.com/CadQuery/cadquery/pull/2042): docs for selector chaining
- [`spxrogers/agentsync`](https://github.com/spxrogers/agentsync/pull/73): skip unsupported Claude LSP settings
- [`vercel/ai`](https://github.com/vercel/ai/pull/15857): caching provider option for AI Gateway
- [`r12habh/ActionScope`](https://github.com/r12habh/ActionScope/pull/87): tests for additional AI agent action detectors
- [`huggingface/lerobot`](https://github.com/huggingface/lerobot/pull/3720): support dataset features with zero-width dimensions
- [`modelcontextprotocol/python-sdk`](https://github.com/modelcontextprotocol/python-sdk/pull/2775): transport security troubleshooting docs
- [`firecrawl/firecrawl`](https://github.com/firecrawl/firecrawl/pull/3704): fix docs example license links
- [`openai/openai-python`](https://github.com/openai/openai-python/pull/3358): import `httpx` in timeout docs example
- [`NousResearch/hermes-agent`](https://github.com/NousResearch/hermes-agent/pulls?q=author%3Apranjalbhatia710): docs, tests, and small config fixes

## Projects worth looking at

- [`cadsmith`](https://github.com/pranjalbhatia710/cadsmith): self-correcting text-to-CAD agent that executes CadQuery code, measures generated geometry, and loops until the model verifies
- [`agent-runlens`](https://github.com/pranjalbhatia710/agent-runlens): local-first CLI for turning raw AI agent traces into readable timelines and failure reports
- [`agent-runtrace`](https://github.com/pranjalbhatia710/agent-runtrace): trace recorder and searchable standalone HTML viewer for AI agent runs
- [`gridmind-campus-monitor`](https://github.com/pranjalbhatia710/gridmind-campus-monitor): interactive 3D campus energy dashboard for ML proxy metering, anomaly detection, and facilities ROI analysis
- [`agent-regression-lab`](https://github.com/pranjalbhatia710/agent-regression-lab): tiny regression tests for AI agent traces, tool calls, and final answers
- [`contrib-radar`](https://github.com/pranjalbhatia710/contrib-radar): ranks GitHub issues for credible, low-spam OSS contributions
- [`cad-agent`](https://github.com/pranjalbhatia710/cad-agent): prompt-to-OpenSCAD starter kit for simple parametric CAD parts
- [`trashmytech`](https://github.com/pranjalbhatia710/trashmytech): AI website stress testing with browser personas, built at HackIllinois 2026
- [`analytics-dashboard`](https://github.com/pranjalbhatia710/analytics-dashboard): vulnerability factor analytics dashboard with TypeScript charts
- [`distraction_dataset`](https://github.com/pranjalbhatia710/distraction_dataset): distraction detection model training pipeline

## Background

Before Purdue, I worked on a mix of engineering, robotics, and operations projects:

- designed drone shell/scaffolding prototypes for deforestation imaging at American University Dubai
- built StickX, an assistive mobility stick with Arduino sensors, object detection, gap tracking, and vibrational direction
- worked on data science for student persona and outlier detection at Invest4Edu
- co-founded Alumnaut, interviewed 300+ students and 100+ alumni, and reached around 5000 students in Dubai
- led a 10 person sustainability drive that collected 7 tons of waste in 10 days

I am trying to get better at building things that are technically real, not just presentable.

## Links

- LinkedIn: https://www.linkedin.com/in/pbhatia007
- GitHub: https://github.com/pranjalbhatia710
