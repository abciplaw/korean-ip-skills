# Korean IP Skills

Open, reusable AI-agent skills for Korean patent and trademark practice.

Maintained by **ABC IP LAW**.

스타트업·중소기업 개발팀이 직접 돌리는 **특허 포트폴리오 발굴 스킬**은 [abciplaw/startup-ip-skills](https://github.com/abciplaw/startup-ip-skills)에 있습니다. For the client-facing patent portfolio discovery skill, see [abciplaw/startup-ip-skills](https://github.com/abciplaw/startup-ip-skills).

## Purpose

This repository develops practical, auditable workflows that AI agents can use to assist Korean IP professionals. The project is intended to be useful across agent environments while also supporting Claude Code as a first-class distribution target.

The project favors:
- source-grounded legal and technical analysis;
- explicit separation of facts, assumptions, and professional judgment;
- matter isolation and confidentiality;
- narrow, auditable changes instead of uncontrolled rewrites;
- human review for consequential legal work;
- jurisdiction and freshness metadata for legal rules.

## Status

Early development. Only reviewed skills should be treated as usable. Planned Korean-IP-specific skills are tracked in [CATALOG.md](CATALOG.md).

## Claude Code

This repository is structured as a Claude Code plugin marketplace.

```text
/plugin marketplace add abciplaw/korean-ip-skills
```

The initial plugin is named `korean-ip`. Installation instructions will be expanded once the first substantive Korean-IP skills reach reviewed status.

## Repository structure

```text
.claude-plugin/          Marketplace metadata
korean-ip/               Claude Code plugin
  .claude-plugin/
  skills/                Installable skill definitions
tests/                   Synthetic acceptance tests
research/                External skill/library reviews
CATALOG.md               Skill roadmap and review status
SECURITY.md              Trust and supply-chain policy
CONTRIBUTING.md          Contribution rules
```

## Confidentiality

This repository contains reusable public workflows only. It must never contain client documents, unpublished inventions, matter facts, credentials, or other confidential material.

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE). Redistributions must carry the NOTICE file (Section 4). The names "ABC IP LAW" and "ABC특허법률사무소" and the firm's logo are not licensed (Section 6).
