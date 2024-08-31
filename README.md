<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Satoru-Bug-Bot</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        h1 {
            font-size: 2.5em;
            color: #333;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .center {
            margin: 20px 0;
        }

        .gif-container {
            margin: 20px 0;
        }

        pre {
            background-color: #eee;
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
            white-space: pre-wrap;
        }

        code {
            display: block;
            padding: 10px;
            background-color: #fafafa;
            border: 1px solid #ccc;
            white-space: pre-wrap;
            overflow: auto;
        }

        .contact-links a {
            display: block;
            margin: 10px 0;
            font-size: 1.2em;
            color: #0066cc;
            text-decoration: none;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }

        .thank-you {
            margin: 30px 0;
            font-size: 1.2em;
            color: #666;
        }
    </style>
</head>

<body>
    <div class="gif-container">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
        <h1>Satoru-Bug-Bot</h1>
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
    </div>

    <div class="center">
        <img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=800&size=28&duration=4000&pause=1000&random=false&width=435&lines=+Satoru-Bug-Bot;WHATSAPP+CRASH+x+BUG+BOT;DEVELOPPER+PAR+SatoruTech"
            alt="Typing SVG" />
    </div>

    <div class="gif-container">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
    </div>

    <section>
        <h2>Instructions de déploiement</h2>
        <p>Si vous souhaitez déployer ailleurs, téléchargez votre <code>creds.json</code> dans le dossier de session après avoir obtenu le code de pair sur Replit.</p>
        <h3>Étapes pour déployer :</h3>
        <ul>
            <li><a href="https://github.com/SatoruTech/Satoru-Bug-Bot/fork" target="_blank">Forker le bot depuis GitHub</a></li>
            <li><a href="https://replit.com/@SatoruTech/SatoruTech-Pair-Code?v=1" target="_blank">Obtenir votre Pair-Code depuis Replit</a></li>
            <li><a href="https://solarhosting.cc/" target="_blank">Déployer sur un Panel</a></li>
            <li><a href="https://replit.com/@SatoruTech/Satoru-Bug-Bot" target="_blank">Déployer sur Replit</a></li>
        </ul>
    </section>

    <section>
        <h3>Tutoriels Vidéos</h3>
        <a href="https://www.youtube.com/@SatoruTech" target="_blank">Chaîne YouTube SatoruTech</a>
    </section>

    <section>
        <h2>Commandes pour déployer le Satoru-Bug-Bot sur un terminal :</h2>
        <pre><code>
sudo apt -y update && sudo apt -y upgrade
sudo apt -y install git ffmpeg curl
curl -fsSL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh
sudo -E bash nodesource_setup.sh
sudo apt-get install -y nodejs
sudo npm install -g yarn
sudo yarn global add pm2
git clone https://github.com/SatoruTech/Satoru-Bug-Bot/
cd Satoru-Bug-Bot
yarn install
npm start
        </code></pre>
    </section>

    <section>
        <h2>Déploiement sur Termux :</h2>
        <pre><code>
termux-setup-storage
apt update && apt upgrade
pkg install bash libwebp git nodejs ffmpeg wget yarn
git clone https://github.com/<votre_nom_utilisateur>/Satoru-Bug-Bot.git
cd Satoru-Bug-Bot
yarn install
npm start
        </code></pre>
        <p>Pour exécuter le bot en continu (peut ne pas fonctionner) :</p>
        <pre><code>
npm i -g forever && forever index.js && forever save && forever logs
        </code></pre>
    </section>

    <section>
        <h2>Windows Cmd & Vs :</h2>
        <p>Télécharger les outils nécessaires :</p>
        <ul>
            <li><a href="https://ffmpeg.org/download.html#build-windows" target="_blank">Télécharger ffmpeg</a></li>
            <li><a href="https://eternallybored.org/misc/wget/releases/" target="_blank">Télécharger wget</a></li>
            <li><a href="https://nodejs.org/en/download/" target="_blank">Télécharger Node.js</a></li>
            <li><a href="https://git-scm.com/downloads" target="_blank">Télécharger Git</a></li>
            <li><a href="https://developers.google.com/speed/webp/download" target="_blank">Télécharger Libwebp</a></li>
        </ul>

        <h3>Commandes :</h3>
        <pre><code>
git clone https://github.com/SatoruTech/Satoru-Bug-Bot/
cd Satoru-Bug-Bot
yarn install
npm start
        </code></pre>
    </section>

    <div class="gif-container">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
    </div>

    <section class="contact-links">
        <h2>Contact</h2>
        <a href="https://whatsapp.com/channel/0029Vanj84h6rsQmGlOrMz1X" target="_blank">Rejoindre le canal officiel WhatsApp</a>
        <a href="https://www.youtube.com/@SatoruTech" target="_blank">Chaîne YouTube SatoruTech</a>
    </section>

    <div class="gif-container">
        <img src="https://media2.giphy.com/media/W9tBvzTXkQopi/giphy.gif?cid=6c09b952xu6syi1fyqfyc04wcfk0qvqe8fd7sop136zxfjyn&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=g"
            alt="Development" width="250">
    </div>

    <div class="thank-you">
        <h2>Remerciements</h2>
        <p>Merci à DGXeon : <a href="https://github.com/DGXeon" target="_blank">https://github.com/DGXeon</a> et à JEANPARKER100 : <a href="https://github.com/JEANPARKER100/PARKY-BUG-BOT" target="_blank">https://github.com/JEANPARKER100/PARKY-BUG-BOT</a> pour la base de données utilisée dans **Satoru Bug Bot**. Votre contribution est essentielle au bon fonctionnement du projet et est grandement appréciée.</p>
    </div>

    <div class="gif-container">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
        <img src="https://i.imgur.com/LyHic3i.gif" alt="Satoru-Bug-Bot">
    </div>
</body>

</html>
