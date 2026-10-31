# SatSSTV pour Mac

[SatSSTV](https://github.com/f4lps/SatSSTV) par F4LPS, pour macOS 11 ou plus récent (Mac Apple et Intel). Vos retours sont les bienvenus.

## Télécharger

➡️ **[Dernière version](https://github.com/f4lps/SatSSTV-Mac/releases/latest)** : `SatSSTV-x.y.z-macOS.dmg`

📖 **[Notice en français (PDF)](https://github.com/f4lps/SatSSTV/raw/main/Notice-SatSSTV.pdf)**

## Installer

1. Ouvrir le `.dmg` et glisser **SatSSTV** dans **Applications**.
2. Ouvrir SatSSTV. macOS le bloque, car l'application n'est pas signée par un compte développeur Apple.
3. Aller dans **Réglages Système › Confidentialité et sécurité**, puis cliquer sur **Ouvrir quand même**.
4. Accepter l'accès au **micro** : sans lui, aucune réception n'est possible.

Si macOS dit que l'application est endommagée, taper ceci dans le Terminal, puis la rouvrir :

```bash
xattr -cr /Applications/SatSSTV.app
```

## À savoir

- Le son du poste passe par sa carte son USB. Pour un SDR ou Icom Remote, il faut un câble audio virtuel comme BlackHole.
- Sans câble CAT : choisir **Aucune (sans CAT)** dans **Radio & audio** ; le PTT passe alors par le VOX du poste ou à la main.
- Avec un câble CAT : choisir le port `/dev/cu.…` du poste, ou passer par Hamlib ou FLRig. OmniRig n'existe pas sur Mac.
- Le Tracker F4LPS n'est pas inclus, et il n'y a pas de mise à jour automatique : revenir sur cette page pour une nouvelle version.

## Donner un retour

Si une carte son manque dans **Radio & audio** ou ne s'ouvre pas, joindre le texte du bouton **📋 Copier le diagnostic audio**.

Ouvrir un [ticket](https://github.com/f4lps/SatSSTV-Mac/issues) en indiquant le modèle de Mac, la version de macOS et ce qui ne marche pas.
