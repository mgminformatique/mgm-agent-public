# Installer MGM Agent Admin et MGM Work

[English instructions](#english) · [Présentation du projet](README.fr.md)

**Version disponible : 1.4.2 · Windows 64 bits**

[Télécharger l’installateur](https://github.com/mgminformatique/mgm-agent-public/releases/download/v1.4.2/Agent-Admin-1.4.2-x64.exe)
· [Tous les fichiers de la release](https://github.com/mgminformatique/mgm-agent-public/releases/tag/v1.4.2)
· [Notes de version](RELEASE-1.4.2.md#français)

## Prérequis

- Un ordinateur Windows 64 bits.
- Une connexion Internet pour le compte, les modèles et les services en ligne.
- Un compte MGM et un forfait adapté aux fonctionnalités souhaitées.

MGM Work, l’espace ShellAmp intégré, est accessible avec Ultra. Les comptes
et abonnements des services tiers restent distincts. La création d’un compte
MGM ne déclenche aucun paiement.

## Installation

1. Téléchargez `Agent-Admin-1.4.2-x64.exe` depuis la release ci-dessus.
2. Comparez l’empreinte SHA-256 avec celle indiquée ci-dessous.
3. Pour une mise à jour, terminez les tâches actives puis fermez Agent Admin
   et MGM Work avant de lancer l’installateur.
4. Ouvrez le fichier `.exe` et suivez les étapes de l’assistant.
5. Lancez Agent Admin, connectez votre compte MGM et choisissez votre modèle.
   Avec Ultra, ouvrez MGM Work depuis Agent Admin pour vos tâches locales.

Si un fichier est encore utilisé, l’installateur 1.4.2 propose **Réessayer** ou
**Annuler** avant de modifier l’installation. Il ne ferme pas de force les
agents. Le code `1618` en mode silencieux ou passif indique cette situation.

## Vérifier le téléchargement

Dans PowerShell, adaptez le chemin au dossier de téléchargement :

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath "$env:USERPROFILE\Downloads\Agent-Admin-1.4.2-x64.exe"
```

Empreinte attendue, identique en majuscules ou en minuscules :

```text
c5ec9f5d7c2e519b1aa498bba03cc330c6bf4a1fc4c6de2e40fb70fa1e5c257b
```

Taille : **409 395 499 octets**. Les fichiers `SHA256SUMS` et
`Agent-Admin-1.4.2-x64.exe.sig` accompagnent la release. La signature `.sig`
sert au mécanisme de mise à jour MGM ; **l’installateur n’a pas de signature
Windows Authenticode**. Une empreinte différente signifie qu’il ne faut pas
utiliser ce téléchargement.

Les archives « Source code » ajoutées automatiquement par GitHub contiennent
la documentation publique de ce dépôt. Pour installer l’application, choisissez
le fichier `.exe` dans les fichiers de la release.

[Signaler un problème d’installation](https://github.com/mgminformatique/mgm-agent-public/issues/new?template=bug_report.yml)
· [Utiliser l’application web](https://agent-ia.mgminformatique.ca)

---

## English

**Available version: 1.4.2 · Windows x64**

[Download the installer](https://github.com/mgminformatique/mgm-agent-public/releases/download/v1.4.2/Agent-Admin-1.4.2-x64.exe)
· [All release files](https://github.com/mgminformatique/mgm-agent-public/releases/tag/v1.4.2)
· [Release notes](RELEASE-1.4.2.md)

You need a 64-bit Windows computer, an Internet connection and an MGM account
with a plan suitable for the features you want to use. MGM Work, the integrated
ShellAmp workspace, is included with Ultra. Third-party accounts and
subscriptions remain separate. Creating an MGM account does not initiate a payment.

1. Download `Agent-Admin-1.4.2-x64.exe` from the release linked above.
2. Compare its SHA-256 checksum with the value below.
3. If updating, finish active tasks and close Agent Admin and MGM Work before
   starting the installer.
4. Open the `.exe` file and follow the installation wizard.
5. Launch Agent Admin, sign in with your MGM account and choose your model.
   With Ultra, open MGM Work from Agent Admin for local tasks.

If a required file is still in use, version 1.4.2 offers **Retry** or **Cancel**
before changing the installation. It does not force-close agents. Silent or
passive installation returns exit code `1618` in this situation.

Check the downloaded file in PowerShell, adjusting the path if necessary:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath "$env:USERPROFILE\Downloads\Agent-Admin-1.4.2-x64.exe"
```

Expected SHA-256, case-insensitive:

```text
c5ec9f5d7c2e519b1aa498bba03cc330c6bf4a1fc4c6de2e40fb70fa1e5c257b
```

File size: **409,395,499 bytes**. The release also includes `SHA256SUMS`
and `Agent-Admin-1.4.2-x64.exe.sig`. The detached `.sig` file is used by MGM's
update verification system; **the installer is not Windows
Authenticode-signed**. Do not use a download whose checksum differs.

GitHub's automatically generated “Source code” archives contain this
repository's public documentation. Choose the `.exe` release asset to install
the application.

Use **Watch → Custom → Releases** on GitHub to follow future versions.

[Report an installation problem](https://github.com/mgminformatique/mgm-agent-public/issues/new?template=bug_report.yml)
· [Use the web app](https://agent-ia.mgminformatique.ca)
· [Back to the overview](README.md)
