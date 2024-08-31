# Satoru-Bug-Bot

![Satoru-Bug-Bot](https://i.imgur.com/LyHic3i.gif)
![Satoru-Bug-Bot](https://i.imgur.com/LyHic3i.gif)

![Typing SVG](https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=800&size=28&duration=4000&pause=1000&random=false&width=435&lines=+Satoru-Bug-Bot;WHATSAPP+CRASH+x+BUG+BOT;DEVELOPPER+PAR+SatoruTech)

---

## Instructions de déploiement

Si vous souhaitez déployer ailleurs, téléchargez votre `creds.json` dans le dossier de session après avoir obtenu le code de pair sur Replit.

### Étapes pour déployer :
- [Forker le bot depuis GitHub](https://github.com/SatoruTech/Satoru-Bug-Bot/fork)
- [Obtenir votre Pair-Code depuis Replit](https://replit.com/@SatoruTech/SatoruTech-Pair-Code?v=1)
- [Déployer sur un Panel](https://solarhosting.cc/)
- [Déployer sur Replit](https://replit.com/@SatoruTech/Satoru-Bug-Bot)

---

## Tutoriels Vidéos
- [Chaîne YouTube SatoruTech](https://www.youtube.com/@SatoruTech)

---

## Commandes pour déployer le Satoru-Bug-Bot sur un terminal :

```bash
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
