# Igor Pinchuk

I work on legacy systems — the ones that outlived their original authors and that
nobody on the team wants to touch. Audits, refactoring, performance, and untangling
business logic that grew for a decade without a plan.

Mostly PHP and Symfony, 15+ years. Based in Bali (UTC+8), working async with teams
in Europe and the UK.

---

## Packages in production

My open-source libraries have been installed **~74,000 times** on Packagist.

| Package | Installs | What it does |
|---------|---------:|--------------|
| [expert-sender-api](https://github.com/somework/expert-sender-api) | 35,800+ | PHP client for the ExpertSender API |
| [composer-symlinks](https://github.com/somework/composer-symlinks) | 24,900+ | Relative symlinks from Composer scripts |
| [offset-page-logic](https://github.com/somework/offset-page-logic) | 6,600+ | Offset/limit ↔ page/page-size conversion |
| [offset-page](https://github.com/somework/offset-page) | 6,400+ | Page-based APIs → offset-based pagination |
| [minjust](https://github.com/somework/minjust) | 670+ | Parser for the RF Ministry of Justice registry |

Recent work:

- **[lockrot](https://github.com/somework/lockrot)** — finds the packages in
  `composer.lock` that quietly stopped being maintained: abandoned flags, branches
  that went quiet while a higher branch kept shipping, branch pins, advisories.
  Composer plugin, PHAR, Action or image. MIT, PHP 7.4+, no runtime dependencies.
  [lockrot.dev](https://lockrot.dev)
- **[indexnowkit](https://github.com/indexnowkit/php)** — IndexNow for PHP. Twelve
  packages: protocol core, adapters for Symfony, Laravel, Yii2, Yii3 and Doctrine,
  and a framework-free CLI. Every adapter runs the same conformance suite.
  [indexnowkit.dev](https://indexnowkit.dev)
- **[cqrs](https://github.com/somework/cqrs)** — Symfony bundle wiring Command,
  Query and Event buses on top of Messenger. Attribute-based handler discovery,
  configurable stamp pipeline, PHPStan level 8.
- **[p2p-path-finder](https://github.com/somework/p2p-path-finder)** — toolkit for
  discovering optimal peer-to-peer conversion paths. Deterministic arithmetic,
  clean domain/application separation.
- **[correlation-id](https://github.com/somework/correlation-id)** — PSR-15
  middleware for correlation ID propagation. Symfony 6/7 or any PSR-15 stack.
- **[dsx](https://github.com/somework/dsx)** — sync files between a Claude Design
  project and a local directory without the bytes passing through a model's
  context. Single Go binary, stdlib only.

---

## What I take on

**Legacy audit.** A written report on a codebase you inherited: module map, risk
areas, upgrade path, prioritised debt. Fixed price, fixed timeline.

**Rescue and refactoring.** Bringing an aging system back under control — PHP and
Symfony upgrades, decomposition, test coverage where there was none.

**Performance.** Finding out why it got slow, and making it not slow.

I work in writing, asynchronously. Time zone overlap with Europe covers the
European morning.

---

## Stack

PHP · Symfony · Doctrine · PostgreSQL · MySQL · Redis · Elasticsearch · RabbitMQ ·
Kafka · Docker · Kubernetes · Terraform · Go · TypeScript · Node · AWS

Day to day I lean heavily on AI agent orchestration — it is how a single engineer
covers ground that used to take a team.

---

## Contact

[i.pinchuk.work@gmail.com](mailto:i.pinchuk.work@gmail.com) · [LinkedIn](https://linkedin.com/in/kolgarn)

Happy to look at a codebase and tell you what I see. Written questions get written
answers — no discovery call required.
