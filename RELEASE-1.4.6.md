# MGM Agent Admin 1.4.6

Windows x64 · November 18, 2026

The integrated MGM engine now continues a conversation in a new tab when its message or context limit is reached. The new tab opens automatically and resumes the same mission. The original transcript, project, model selection, reasoning effort, plan and checkpoint are retained. The engine reads the original requests before taking further actions.

The mission keeps its shared points ceiling and account balance. Pending approvals, uncertain actions, cancellations and exhausted budgets prevent an automatic restart. Session permissions are not copied to a new tab, and previous tool calls are not replayed. A model whose window is too small for even a short conversation needs a larger context configuration.

This release includes the integrated MGM engine, the complete MGM Work / ShellAmp runtime, the Windows sign-in fixes prepared for 1.4.5 and the CAD display correction. Existing accounts and saved connections are retained. The public Windows app connects to the MGM service; desktop actions still run on the user's PC with its permissions.

Validation: 1,104 isolated tests passed; three optional tests were skipped. TypeScript validation and the version-bound MGM update signature check passed. HTTP and asset checks are performed before publication. These checks do not certify authorization of your third-party accounts or perfect model behavior.

The installer has an MGM update signature and SHA-256 checksums. It does not have a Windows Authenticode signature. Finish active tasks and close Agent Admin and MGM Work before updating. See [installation instructions](INSTALLATION.md#english).

## Français

Windows 64 bits · 18 novembre 2026

Le moteur MGM intégré poursuit maintenant la conversation dans un nouvel onglet quand sa limite de messages ou de contexte est atteinte. L'onglet s'ouvre automatiquement et reprend la même mission. L'historique original, le projet, le modèle, l'effort, le plan et le point de reprise sont conservés. Le moteur relit les demandes originales avant de lancer de nouvelles actions.

La mission conserve son plafond commun de points et le solde du compte. Une approbation en attente, une action incertaine, une annulation ou un budget épuisé empêchent le redémarrage automatique. Les autorisations de session ne sont pas copiées dans un nouvel onglet et les anciens appels d'outils ne sont pas rejoués. Si la fenêtre du modèle est trop petite même pour un fil court, sa configuration doit être adaptée.

Cette version comprend le moteur MGM intégré, le runtime MGM Work / ShellAmp complet, les correctifs de connexion Windows préparés pour la 1.4.5 et le correctif d'affichage CAD. Les comptes et les connexions enregistrées sont conservés. L'application Windows publique se connecte au service MGM ; les actions sur le poste gardent les autorisations de l'ordinateur.

Validation : 1 104 tests isolés réussis, trois essais optionnels ignorés. La vérification TypeScript et celle de la signature de mise à jour liée à cette version ont réussi. Les contrôles HTTP et des fichiers servis sont effectués avant publication. Ces contrôles ne certifient ni l'autorisation de vos comptes tiers ni un suivi parfait des consignes par les modèles.

L'installateur possède une signature de mise à jour MGM et des empreintes SHA-256. Il n'a pas de signature Windows Authenticode. Terminez les tâches actives et fermez Agent Admin et MGM Work avant de l'installer. Consultez les [instructions d'installation](INSTALLATION.md).
