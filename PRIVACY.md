# RecentDrop — Privacy Policy / Politique de confidentialité

_Last updated / Dernière mise à jour : 2026-05-31_

---

## English

RecentDrop is a macOS menu-bar utility that lists your recent files and generates
cloud share links. Your privacy is fundamental to how the app is built.

### No servers, no collection
RecentDrop has **no backend server**. The developer does not operate any service
that receives, stores, or processes your files, file names, or personal data.
All processing happens **locally on your Mac**.

### Direct communication with official cloud APIs
When you request a share link, the app communicates **directly from your Mac** with
the official API of the relevant service, using **your own credentials**:

- Google Drive — `googleapis.com`
- Microsoft OneDrive — `graph.microsoft.com`, `login.microsoftonline.com`
- Dropbox — `api.dropboxapi.com`
- Infomaniak kDrive — `api.infomaniak.com`
- License validation — `api.gumroad.com`

No other network destinations are contacted. There is **no analytics or telemetry**.

### Your credentials stay on your device
API tokens, OAuth client IDs/secrets, and refresh tokens are stored **encrypted in
the macOS Keychain** on your machine. They are **never transmitted to the developer**
and are only sent to the corresponding official cloud API to fulfill your request.

### Minimal access
The app only reads the folders you explicitly add, solely to display your recent
files and to generate share links when you ask for them. It does not scan your disk,
read your browsing history, or access unrelated data.

### Your control
You can disconnect any cloud service or clear its credentials at any time from
Settings. Removing a token deletes it from the Keychain.

### Contact
For any question: mysteropodes@gmail.com

---

## Français

RecentDrop est un utilitaire macOS (barre de menus) qui liste vos fichiers récents
et génère des liens de partage cloud. Le respect de votre vie privée est au cœur de
sa conception.

### Aucun serveur, aucune collecte
RecentDrop n'a **aucun serveur**. Le développeur n'exploite aucun service recevant,
stockant ou traitant vos fichiers, noms de fichiers ou données personnelles.
Tout le traitement se fait **localement sur votre Mac**.

### Communication directe avec les API officielles
Lorsque vous demandez un lien de partage, l'app communique **directement depuis votre
Mac** avec l'API officielle du service concerné, avec **vos propres identifiants** :

- Google Drive — `googleapis.com`
- Microsoft OneDrive — `graph.microsoft.com`, `login.microsoftonline.com`
- Dropbox — `api.dropboxapi.com`
- Infomaniak kDrive — `api.infomaniak.com`
- Validation de licence — `api.gumroad.com`

Aucune autre destination réseau n'est contactée. **Aucun analytics ni télémétrie.**

### Vos identifiants restent sur votre appareil
Les tokens d'API, identifiants OAuth et refresh tokens sont stockés **chiffrés dans le
Trousseau macOS** de votre machine. Ils ne sont **jamais transmis au développeur** et
ne sont envoyés qu'à l'API officielle correspondante pour exécuter votre demande.

### Accès minimal
L'app ne lit que les dossiers que vous ajoutez explicitement, uniquement pour afficher
vos fichiers récents et générer des liens à votre demande. Elle ne scanne pas votre
disque, ne lit pas votre historique de navigation et n'accède à aucune donnée non liée.

### Votre contrôle
Vous pouvez déconnecter un service cloud ou effacer ses identifiants à tout moment
depuis les Réglages. Supprimer un token le retire du Trousseau.

### Contact
Pour toute question : mysteropodes@gmail.com
