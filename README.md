<h1 align="center">🔗 Naoki V2 🚀</h1>

**NOTE:** \
Ce bot n'a pas été fait par moi, j'ai simplement retiré quelque bugs et les remit sur github !

---
## <a id="menu"></a>🔱 » Menu

- [🔰・Fonctionnalitées](#features)
- [🌌・Discord](https://discord.gg/qTzmGuEx7a)
- [🎉・Lancement](#setup)
- [⚙・Config](#config)

## <a id="features"></a>🛠 » Features

```
> Commandes Admin
> Commandes Modération
> Commandes Gestion
> Commandes Anti Raid
> Commandes Jeux
> Commandes Utilitaires
> Commandes Musiques
> Commandes Logs
> Commandes Owners
> Système de Tickets
> Système de Pfp
> Système de Soutien
```

## <a id="setup"></a> 📁 » Setting up 

1. Installez [Nodejs](https://nodejs.org/ko/blog/release/v16.19.0/)
2. Ouvrez le fichier `config.js` avec le bloc-note ou autre
3. Ouvrez un terminal dans le répertoire des fichiers
4. Entrez la commande `npm i && node index`
5. Vous Pouvez aussi hébèrger votre bot sur ce serveur : [Serveur](https://discord.gg/qTzmGuEx7a)

# <a id="config"></a>⚙ » Config

Pour configurer le fichier `config.js`, vous pouvez suivre l'exemple ci-dessous:

```js
module.exports = {
    app: {
        px: '+',
        token: 'NzgxMjA0ODUyOTEwOTgxMTYz.GkAM43.t0y1bsPwdKBkfIoU_LWh04eOtNcekjPbCFwRz0',
        owners: '458276816071950337',
        funny: '458276816071950337',
        color: '#0000FF',
        footer: 'Oauth2 Bot',
        maxserver: '1',
        maxVol: '150',
        everyoneMention: false,
        hostedBy: true,
        discordPlayer: {
            ytdlOptions: {
                quality: 'highestaudio',
                highWaterMark: 1 << 25
            }
        }
    }
}
```
