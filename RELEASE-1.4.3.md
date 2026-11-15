# MGM Agent Admin & MGM Work 1.4.3

Windows x64 · November 15, 2026

Version 1.4.3 brings the R4 task continuity improvements to Agent Admin and MGM Work, simplifies the shared model picker and adds the official Stripe connection flow.

- Requested deliverables stay visible independently of the model's plan. Available evidence and human review have separate states.
- Interrupted sessions retain previous tool results, pending approvals and later instructions. Work reports the server's final status.
- Compatible local plugins and skills are available through the MGM Work bridge, with their existing approval requirements.
- The shared OpenRouter picker keeps the original DeepSeek V4.1 Flash, DeepSeek V4 Pro, GLM 5.3 Flash, GLM 5.3 and Kimi K3 choices, alongside MGM modes. Plan restrictions still apply. Personal API connections and supported Hugging Face inference remain available.
- Stripe connects through its official authorization page. Authorize your Stripe account in Agent Admin; the separate Mission Control connection does not transfer automatically.

The installer retains the resource checks introduced in 1.4.2. Finish active work and close Agent Admin and MGM Work before updating. The installer does not force-close agents.

Validation: 837 application tests and 18 funding tests passed, with three optional tests skipped. The Linux build, production identity and HTTP/assets were checked separately. Model responses in the automated scenarios are simulated. A live model acceptance test and visual verification of this release have not been completed.

The release includes the Windows installer, its detached MGM update signature and `SHA256SUMS`. The installer does not have a Windows Authenticode signature. This public repository contains documentation; the application source remains private.

## Français

Windows 64 bits · 15 novembre 2026

La version 1.4.3 réunit les correctifs R4 de continuité des tâches, le sélecteur de modèles simplifié et la connexion officielle Stripe.

- Les livrables demandés restent visibles indépendamment du plan du modèle. Les preuves disponibles et la revue humaine ont des états distincts.
- La reprise conserve les résultats d'outils, les approbations et les nouvelles consignes. MGM Work consulte l'état final du serveur.
- Les plugins locaux et compétences compatibles sont accessibles par le pont MGM Work, selon leurs autorisations habituelles.
- Le sélecteur OpenRouter conserve les cinq modèles d'origine : DeepSeek V4.1 Flash, DeepSeek V4 Pro, GLM 5.3 Flash, GLM 5.3 et Kimi K3, avec les modes MGM et les restrictions de forfait. Les connexions API personnelles et l'inférence Hugging Face compatible restent disponibles.
- Stripe passe par sa page officielle d'autorisation. Il faut autoriser le compte dans Agent Admin ; la connexion distincte de Mission Control n'est pas transférée automatiquement.

L'installateur conserve le contrôle des fichiers utilisés introduit dans la 1.4.2. Terminez les tâches en cours et fermez Agent Admin et MGM Work avant la mise à jour. Aucun agent n'est fermé de force.

Vérifications : 837 tests applicatifs et 18 tests de financement réussis ; trois tests facultatifs ignorés. Compilation Linux, identité de production, HTTP et fichiers servis vérifiés séparément. Les scénarios automatisés utilisent des réponses de modèles simulées. L'essai avec un vrai modèle et la vérification visuelle de cette version restent à faire.

La release contient l'installateur, sa signature de mise à jour MGM et `SHA256SUMS`. L'installateur n'a pas de signature Windows Authenticode. Ce dépôt public contient la documentation ; le code applicatif reste privé.
