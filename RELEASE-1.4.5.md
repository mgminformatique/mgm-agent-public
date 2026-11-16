# MGM Agent Admin 1.4.5

Windows x64 · November 16, 2026

Version 1.4.5 fixes the launch of the official sign-in windows.

- **Supabase:** fixes the dedicated CLI profile and gives its Windows console real interactive input and output. The sign-in prompt stays open instead of exiting immediately.
- **Microsoft 365 and Stripe:** opens the authorization browser on the first click. If Windows or the browser refuses, MGM displays the error and keeps the code or retry link available.
- **Account confirmation:** the account still needs to be checked and confirmed inside MGM before association. Existing saved connections are retained until that confirmation.

The complete MGM Work runtime, the five original OpenRouter choices and the CAD display correction are preserved. Update both the Windows app and the server for the new browser opener. Finish active work and close Agent Admin and MGM Work before installing.

GitHub, Netlify and Supabase require their official Windows CLI. Google Cloud/Gmail require MGM OAuth configuration. Docker Hub/GoDaddy do not provide a new keyless association in this release.

Validation: 36 targeted web tests, 33 Windows Rust tests and nine simulated interface scenarios passed. A Windows GUI probe verified real console handles; the installed Supabase CLI remained at its interactive prompt in an isolated, bounded test. All 1,670 packaged resource files were compared, including 179 MGM Work runtime files. Server HTTP and asset checks run separately before publication. Authorization with a real provider account remains to be completed by the account owner; these checks do not establish that an account is connected. Responsive visual acceptance is still in progress.

The installer includes a version-bound MGM update signature and SHA-256 checksums. It does not have a Windows Authenticode signature. See [installation instructions](INSTALLATION.md#english).

## Français

Windows 64 bits · 16 novembre 2026

La 1.4.5 corrige l’ouverture des fenêtres de connexion officielles.

- **Supabase :** corrige le profil CLI dédié et fournit une vraie entrée et sortie interactives à sa console Windows. L’invite de connexion reste ouverte au lieu de se fermer immédiatement.
- **Microsoft 365 et Stripe :** ouvre le navigateur d’autorisation dès le premier clic. Si Windows ou le navigateur refuse, MGM affiche l’erreur et conserve le code ou le lien pour réessayer.
- **Confirmation du compte :** le compte doit toujours être vérifié et confirmé dans MGM avant l’association. Les connexions enregistrées sont conservées jusqu’à cette confirmation.

Le runtime MGM Work complet, les cinq modèles OpenRouter d’origine et le correctif d’affichage CAD sont conservés. L’application Windows et le serveur doivent être à jour pour le nouvel ouvreur. Terminez vos tâches actives et fermez Agent Admin et MGM Work avant l’installation.

GitHub, Netlify et Supabase nécessitent leur outil officiel Windows. Google Cloud/Gmail nécessitent la configuration OAuth MGM. Docker Hub/GoDaddy ne proposent pas de nouvelle association sans clé dans cette version.

Validation : 36 tests web ciblés, 33 tests Rust Windows et neuf parcours d’interface simulés réussis. Une sonde Windows a vérifié les entrées et sorties de console ; la CLI Supabase installée est restée sur son invite interactive pendant un essai isolé et limité. Les 1 670 fichiers du paquet ont été comparés, dont les 179 fichiers du runtime MGM Work. Les contrôles HTTP et des ressources du serveur sont exécutés séparément avant publication. L’autorisation sur un vrai compte reste à effectuer par son propriétaire ; ces tests ne prouvent pas qu’un compte est connecté. La recette visuelle des formats d’écran est encore en cours.

L’installateur est accompagné d’une signature MGM liée à la version et des empreintes SHA-256. Il n’a pas de signature Windows Authenticode. Voir le [guide d’installation](INSTALLATION.md).
