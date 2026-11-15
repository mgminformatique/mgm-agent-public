# MGM Agent Admin 1.4.4

Windows x64 · November 15, 2026

Version 1.4.4 replaces manual credential forms in the Connections dialogs with
the available official authorization flows. It adds the Windows bridge needed
to associate an authorized account with your MGM agent.

- **GitHub, Netlify and Supabase:** the installed official CLI opens its sign-in flow. Complete authorization in its window/browser, then check and confirm the account shown in Agent Admin. The corresponding official CLI must be installed.
- **Microsoft 365 and Stripe:** their existing official authorization flows remain available when configured.
- **Google Cloud and Gmail:** require MGM's OAuth application configuration before sign-in is available.
- **Docker Hub and GoDaddy:** the dialogs explain that a new keyless server association is unavailable. Opening the provider's account page does not connect it to MGM.

The nine dialogs no longer ask you to paste a key, JSON credential or app
password. Existing saved connections are retained until you confirm a replacement.
Account verification happens on the MGM server; credentials are not returned to
the page. Cancellation, expiration and rejected authorization do not mark a
service as connected.

The Windows application **and** the server need this update for the new bridge.
Finish active work and close Agent Admin and MGM Work before installing.
Task continuity, the five original OpenRouter choices and the MGM Work runtime
from 1.4.3 are retained.

Validation of the prepared candidate: 864 application tests, 34 Windows Rust
tests, eight simulated UI scenarios and eight isolated HTTP checks passed.
A separate recheck passed 35 connector tests. Provider authorization in a real
user account and native visual acceptance remain to be completed; simulated
responses do not establish that a provider account is connected.

The release includes the installer, its version-bound MGM update signature and
`SHA256SUMS`. The installer does not have a Windows Authenticode signature.
See [installation instructions](INSTALLATION.md#english).

## Français

Windows 64 bits · 15 novembre 2026

La 1.4.4 remplace les formulaires manuels des fenêtres Connexions par les
parcours d'autorisation officiels disponibles. Elle ajoute le pont Windows
nécessaire à l'association du compte autorisé avec l'agent MGM.

- **GitHub, Netlify et Supabase :** l'outil officiel installé lance la connexion. Terminez l'autorisation dans sa fenêtre et le navigateur, puis vérifiez et confirmez le compte affiché dans Agent Admin. L'outil officiel correspondant doit être installé.
- **Microsoft 365 et Stripe :** les parcours officiels existants restent disponibles lorsqu'ils sont configurés.
- **Google Cloud et Gmail :** la configuration de l'application OAuth MGM reste nécessaire avant la connexion.
- **Docker Hub et GoDaddy :** les fenêtres expliquent que l'association serveur sans clé n'est pas disponible. Ouvrir le site officiel n'associe pas le compte à MGM.

Les neuf fenêtres ne demandent plus de coller une clé, un fichier JSON ou un
mot de passe d'application. Les connexions enregistrées sont conservées jusqu'à
la confirmation d'un remplacement. Le serveur MGM vérifie le compte sans
renvoyer les identifiants à la page. Une annulation, une expiration ou un refus
ne marque jamais un compte comme connecté.

Il faut mettre à jour **l'application Windows et le serveur** pour utiliser ce
nouveau pont. Terminez les tâches actives et fermez Agent Admin et MGM Work
avant l'installation. La continuité des tâches, les cinq modèles OpenRouter
d'origine et le runtime MGM Work de la 1.4.3 sont conservés.

Validation du candidat préparé : 864 tests applicatifs, 34 tests Rust Windows,
huit parcours d'interface simulés et huit contrôles HTTP isolés réussis.
Une nouvelle vérification a passé 35 tests de connexion. L'autorisation sur
un vrai compte et la recette visuelle native restent à effectuer ; les réponses
simulées ne prouvent pas qu'un compte fournisseur est connecté.

La release contient l'installateur, sa signature de mise à jour MGM liée à la
version et `SHA256SUMS`. L'installateur n'a pas de signature Windows Authenticode.
Voir le [guide d'installation](INSTALLATION.md).
