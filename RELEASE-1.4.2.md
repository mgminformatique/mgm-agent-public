# MGM Agent Admin & MGM Work 1.4.2

**Windows x64 · Public installer release**

[Download the Windows installer](https://github.com/mgminformatique/mgm-agent-public/releases/download/v1.4.2/Agent-Admin-1.4.2-x64.exe)
· [All release files](https://github.com/mgminformatique/mgm-agent-public/releases/tag/v1.4.2)
· [Installation guide](INSTALLATION.md#english)

## What's included

- MGM Agent Admin for Windows, connected to the MGM web application.
- MGM Work, the integrated ShellAmp workspace, available with the Ultra plan.
- Graphite styling, terminal tabs, slash-command suggestions, Tab completion,
  searchable model selection and multiline input in the MGM prompt.
- The bundled library of 50 extensions and themes, with project tools,
  command recipes and the supported agent profiles.

Version **1.4.2 fixes installation when an older MGM Work process is still
using a bundled file**. The installer checks resources before modifying the
existing installation. It offers Retry or Cancel without force-closing an
agent. Silent or passive installation exits with code `1618` while a required
resource remains in use.

This public release distributes the previously validated 1.4.2 installer
unchanged. It does not include unfinished development changes. Online model
availability and service features depend on your account, plan and connections.
Third-party agent and service subscriptions remain separate.

## Download and verification

| File | Purpose |
| :--- | :--- |
| `Agent-Admin-1.4.2-x64.exe` | Windows x64 installer — 409,395,499 bytes. |
| `Agent-Admin-1.4.2-x64.exe.sig` | Detached signature used by the MGM update verification system. |
| `SHA256SUMS` | SHA-256 checksums for the installer and its signature. |

Installer SHA-256:

```text
c5ec9f5d7c2e519b1aa498bba03cc330c6bf4a1fc4c6de2e40fb70fa1e5c257b
```

The update signature and signed version have been verified. **The installer
is not Windows Authenticode-signed**; the detached update signature is a
different mechanism. See the [installation guide](INSTALLATION.md#english)
to compare the downloaded file's checksum.

The automatically generated GitHub “Source code” archives contain this
repository's public documentation. Use the `.exe` asset to install the app.
The proprietary application source is not distributed here.

## Validation of this package

The original 1.4.2 validation covered eight real Windows installer-lock
scenarios, 1,660 extracted resources, 174 runtime files, 50 plugins and
13 checks in the packaged MGM Windows terminal. Remote model responses in
those terminal checks were simulated. No paid-model performance claim is
made by these checks. For this public mirror, the installer and signature
were checked again against the validated release and the update signature
was verified again.

## Français

**L’installateur Windows 64 bits 1.4.2 est disponible dans les fichiers de cette
release.** Il inclut Agent Admin et MGM Work, l’espace ShellAmp accessible avec
Ultra, avec les thèmes et extensions incluses.

Cette version corrige l’installation lorsqu’un ancien processus MGM Work
utilise encore un fichier. Le contrôle intervient avant toute modification et
propose Réessayer ou Annuler, sans fermer de force les agents. Une installation
silencieuse ou passive renvoie le code `1618` si une ressource reste utilisée.

Le fichier est identique à la version 1.4.2 déjà validée. L’empreinte SHA-256
et la signature de mise à jour sont fournies ; le programme n’est pas signé
avec un certificat Windows Authenticode. Les abonnements tiers restent
distincts du forfait MGM.

[Guide d’installation français](INSTALLATION.md) ·
[Présentation du projet](README.fr.md) ·
[Signaler un problème](https://github.com/mgminformatique/mgm-agent-public/issues/new?template=bug_report.yml)
