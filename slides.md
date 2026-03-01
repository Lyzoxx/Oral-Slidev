---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=1
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: fade
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 5min
---

<div class="absolute top-6 left-8 text-left">
  <div class="text-2xl">COLLEGE JEAN MONNET</div>
  <div class="text-xl">6 ALLÉE DE LA VIGNE DE PÂQUES, 44120 VERTOU</div>
</div>

<div class="absolute bottom-6 right-8 text-right text-lg">
  Crafting Tech, 41 route de pont Saint Martin, Vertou
</div>

<div class="absolute bottom-6 left-8 text-left text-lg">
  Renaudineau, Liam, 3C, 2025/2026
</div>

<div class="flex items-center justify-center min-h-[50vh]">
  <h1 class="text-center">RAPPORT DE STAGE</h1>
</div>

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=4
---

<div class="absolute top-6 left-0 right-0 text-center text-4xl font-bold">
  Sommaire
</div>
<ul class="absolute top-24 left-12 md:left-20 text-left text-xl list-disc list-inside space-y-2">
  <li>Introduction</li>
  <li>Présentation de l'entreprise</li>
  <li>Le métier d'ingénieur logiciel</li>
  <li>Mon expérience</li>
  <li>Conclusion</li>
</ul>

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=3
---

<div class="absolute top-8 left-0 right-0 text-center text-4xl font-bold">
  Introduction
</div>
  <ul class="absolute top-24 left-12 md:left-20 text-left text-2xl list-disc list-inside space-y-2">
  <br>
    <li>Secteur d'activité</li>
  <li>Choix de l'entreprise :</li>
    <li class="font-serif font-light" style="list-style: none;">– Obtention du stage</li>
    <li class="font-serif font-light" style="list-style: none;">– Manière pour le trouver</li>
    <li class="font-serif font-light" style="list-style: none;">– Méthodes</li>
  </ul>

<!--
Où le stage ?

Stage obtenu ?

Méthodes ?
-->

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=2
---

<div class="absolute top-8 left-0 right-0 text-center text-4xl font-bold">
  Présentation de l'entreprise
</div>

<!-- Gauche : Crafting Tech + flèche à droite + Brendan Gouin -->
<div class="absolute left-12 top-1/2 -translate-y-1/2 z-10 flex items-center gap-4">
  <div class="flex flex-col items-center">
    <div class="rounded overflow-hidden" style="background: #5a5a5a;">
      <img src="https://craftingtech.fr/assets/logo-ClPFe5ny.png" alt="Logo Crafting Tech" class="object-contain max-h-28 w-auto block" style="mix-blend-mode: multiply;" />
    </div>
    <p class="mt-2 text-xl font-medium">Brendan Gouin (tuteur)</p>
  </div>
  <span class="text-8xl text-white/90 shrink-0">→</span>
</div>

<!-- Droite : LePlein + Son client (plus proche de la flèche) -->
<div class="absolute right-[28%] top-1/2 -translate-y-1/2 z-10 flex flex-col items-center">
  <img src="data:image/jpeg;base64,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" alt="Logo LePlein" class="object-contain max-h-40" />
  <p class="mt-2 text-xl font-medium">Son client</p>
</div>

<!--
Nom, ce que c'est, Lieux

Secteur écono et secteur activité 

enttreprise privée, salariés, historique
-->

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=4
---

<div class="absolute top-8 left-0 right-0 text-center text-4xl font-bold">
  Le métier d'ingénieur logiciel
</div>
<div class="absolute top-24 left-8 text-left text-2xl">
  1) Sa formation
</div>
<div class="absolute top-36 left-8 text-left text-2xl">
  2) Sa journée de travail 
</div>
<div class="absolute top-48 left-8 text-left text-2xl">
  3) Avantages et Inconvénients
</div>

<!--
Sa formation: 

Son métier, 
Son parcours, 
Diplome pour y accéder, 
Salaire débutant

Équipes ?

Outils ou Instruments ?

Conditions travail ?
-->

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=3
---

<div class="absolute top-8 left-0 right-0 text-center text-4xl font-bold z-10">
  Mon expérience
</div>
<ul class="absolute top-35 left-12 md:left-20 text-left text-xl list-disc list-inside space-y-2">
  <li>1) Ma journée de travail</li>
  <li>2) Mes impressions</li>
</ul>
<div class="absolute bottom-8 right-8 z-10">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Logo_Polytech_Angers.svg/500px-Logo_Polytech_Angers.svg.png" alt="Logo Polytech Angers" class="object-contain max-h-32" />
</div>
<div class="absolute top-8 left-8 z-10">
  <img src="https://coworking-colibri.fr/wp-content/uploads/2025/03/logo_colibri_couleur.svg" alt="Coworking Colibri" class="object-contain max-h-52" />
</div>

<!--
Ma journée type

Durée stage

Modif idée initial

Opinion vie pro

Nouv métier ?

Regret ?

Plus apprécié ?
-->

---
transition: fade-out
layout: cover
background: https://picsum.photos/id/1/1920/1080?grayscale&blur=2
---

<div class="absolute top-8 left-0 right-0 text-center text-4xl font-bold">
  Conclusion
</div>

<!--
vision monde du travail ?

Projet perso ?

Changement orientation sco ?

Info constr orientation
-->
