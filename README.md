# BancontactPro.SDK

> **This is not an official Bancontact project.** These SDKs are developed independently, based on the public Bancontact Pro documentation. They are not made, approved or supported by Bancontact (or Payconiq). "Bancontact" and "Bancontact Pro" are names of their owners and are used here only to describe compatibility. The copyright holder claims no right in those names (see [NOTICE](NOTICE)).

Unofficial, independent, open source SDKs for the Bancontact Pro API (.NET, TypeScript, Python, PHP): overview, documentation, bug reports and samples.

> **Status: early.** No package has been published yet and no package names are reserved.

## SDKs

| Language | Repository | Package name (proposal, not reserved) |
|---|---|---|
| .NET | [BancontactPro.Net](https://github.com/yvebrecht/BancontactPro.Net) | `BancontactPro.Net` (NuGet) |
| TypeScript | [BancontactPro.TypeScript](https://github.com/yvebrecht/BancontactPro.TypeScript) | `@yvebrecht/bancontactpro` (npm) |
| Python | [BancontactPro.Python](https://github.com/yvebrecht/BancontactPro.Python) | `bancontactpro` (PyPI) |
| PHP | [BancontactPro.PHP](https://github.com/yvebrecht/BancontactPro.PHP) | `yvebrecht/bancontactpro` (Packagist) |

The names are proposals following each ecosystem's usual conventions. Nothing is reserved or published.

## Versioning

All SDKs use [SemVer](https://semver.org/) in the same format, for example `0.2.0-preview.1`, with git tags such as `v0.2.0-preview.1`.

- **Major and minor are the same across all languages.** The same `0.2` means the same functional level in .NET, TypeScript, Python and PHP.
- **Patch and the prerelease part are free per language.** A bug fix in one SDK only raises that SDK's patch.
- Some ecosystems write versions differently. PyPI uses PEP 440, so `0.2.0-preview.1` appears there as `0.2.0rc1`. It is the same version, spelled the way that ecosystem requires.

## Samples

Each language has a small web UI to try a payment by hand against Bancontact's preprod with the Bancontact Pay test app, with the debug information of every call: [.NET](https://github.com/yvebrecht/BancontactPro.SDK.Samples.Net), [TypeScript](https://github.com/yvebrecht/BancontactPro.SDK.Samples.TypeScript), [Python](https://github.com/yvebrecht/BancontactPro.SDK.Samples.Python) and [PHP](https://github.com/yvebrecht/BancontactPro.SDK.Samples.PHP). They build on the sister repositories until the packages are published.

## Licence

The SDKs, the samples and this repository are licensed under the **Apache License 2.0** (see [LICENSE](LICENSE) and [NOTICE](NOTICE)). Copyright 2026 Axel Dewaele. There is no registration, no licence key and no fee, and the SDKs have no telemetry.

The licence covers the code. It gives no right in the Bancontact trademarks, and the copyright holder does not claim any.

## Transparency: AI-assisted development

The SDKs and their documentation are developed with the help of AI tools, including Claude from Anthropic, under the direction and review of the maintainer. The maintainer remains responsible for the releases he publishes.

## Bug reports and contributions

Open an [issue](https://github.com/yvebrecht/BancontactPro.SDK/issues) with one of the templates, or see [CONTRIBUTING.md](CONTRIBUTING.md). Report vulnerabilities as described in [SECURITY.md](SECURITY.md).

**Issues are public. Never post API keys, private keys, production merchant profile IDs, payment data or personal data.**

## Documentation

[`docs/`](docs/Home.md): overview and roadmap.

---

## Nederlandse samenvatting

Dit is **geen officieel Bancontact-project**. Het zijn onafhankelijke, open-source SDK's voor de Bancontact Pro-API (.NET, TypeScript, Python, PHP), ontwikkeld op basis van de openbare documentatie. De rechthebbende maakt geen aanspraak op de merken Bancontact en Bancontact Pro (zie [NOTICE](NOTICE)).

- **Licentie:** Apache License 2.0, copyright 2026 Axel Dewaele. Geen registratie, geen licentiesleutel, geen vergoeding en geen telemetrie.
- **Versies:** SemVer in hetzelfde formaat voor alle SDK's (bijvoorbeeld `0.2.0-preview.1`). Major en minor zijn gelijk over alle talen; patch en het prerelease-deel zijn vrij per taal.
- **Status:** er is nog niets gepubliceerd.
- **Melden:** bugs en vragen via de [issues](https://github.com/yvebrecht/BancontactPro.SDK/issues). Issues zijn publiek: plaats er geen sleutels of betaalgegevens in.
- **AI:** de SDK's en de documentatie worden ontwikkeld met hulp van AI (Anthropic Claude), onder leiding en controle van de maintainer.