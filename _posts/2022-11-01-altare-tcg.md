---
title: Accessible Trading Card Pack Opening Game
categories:
- Project management
- Accessibility
- Remote
featured_image: "/assets/2022-altare-tcg/1-playing-on-stream.png"
image_alt: Altare poking his head over the site window and opening a card pack live on stream. The hyped chat is spamming his custom heart emojis, saying "SO COOL!". Magni Dezmond, another streamer in Altare's guild, comments "wait what in the actual fuck this is insane"
---

[Regis Altare](https://www.youtube.com/@RegisAltare) themed booster pack opening simulator so you can try your luck in pulling fan-created cards!

🌟 Live at [https://altarebday2023.com/](https://altarebday2023.com/)

🎬 [Altare showcasing the site on his birthday stream!](http://www.youtube.com/watch?v=42uQ_AvFaFk&t=1475)
[![Altare poking his head over the site window and opening a card pack live on stream. The hyped chat is spamming his custom heart emojis, saying "SO COOL!". Magni Dezmond, another streamer in Altare's guild, comments "wait what in the actual fuck this is insane"](/assets/2022-altare-tcg/1-playing-on-stream.png)](http://www.youtube.com/watch?v=42uQ_AvFaFk&t=1475)

## Overview
- Role: Technical project manager, code reviewer
- Team: Project manager, 3 other software engineers (international remote)
- Timeline: 10 weeks

## Competencies demonstrated

- Working international remote; async communication
- Chose tech stack and wrote spec
- Implementing keyboard and live announcement support for game interactions
- Mentoring teammates to incorporate accessibility into their changes

## Features
Cards have rarities (Common, Uncommon, Rare, Holo rare, Ultra rare, Secret rare) and animations as inspired by the official Pokemon TCG. Thanks to [https://github.com/simeydotme/pokemon-cards-css](pokemon-cards-css) for the animations!

{% gif /assets/2022-altare-tcg/2-card-flipping.gif "A pile of face-down cards flip to the left on click, revealing Uncommon, Rare, and finally an Ultra Rare. The Rare is slightly shinier than the Uncommon, and the Ultra Rare has a rainbow gradient and fine, wavy foil texture." %}

Tracks collected cards and total pulls

<img alt="Collections tab on site showing 33 out of 290 cards pulled, 4 total pulls, and a gallery of the collected cards" src="/assets/2022-altare-tcg/3-collection.png">

Screenreader and keyboard control compatible, as well as other accessibility features like skip link and disabling animations

{% include video.html id="/assets/2022-altare-tcg/a11y-demo.mov" title="Accessibility demo" %}

Contributor messages, fan messages, and credits pages

<img alt="Contributor messages page with the header 'Happy Birthday Altare,
from all staff, artists and writers who worked on this project!' with message cards containing birthday wishes" src="/assets/2022-altare-tcg/4-credits.png"> 
<img alt="Message board page with video embed showing art of Altare's official mascot T-posing and the artist's birthday message. The text above says 'This preview is best viewed on desktop.
To see the messages in full, view the original message wall.'" src="/assets/2022-altare-tcg/5-fan-msgs.png">
<img alt="Credits and download page showing 'Download full project PDF' and 'View Accessible Project Format' buttons. Below shows a snippet of the list of General/ Management and Website Development credits." src="/assets/2022-altare-tcg/6-downloads.png">

You can pet him!

{% gif /assets/2022-altare-tcg/6-pet.gif "Chibi Altare with a cat mouth grin peeking out over the site's main content area. He is swaying back and forth while a hand cusor furiously pets his head. The Home button pokes out at an angle behind him." %}