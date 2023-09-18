# Gerede
Un peu tout et n'importe quoi


# Mémo gpt
text2graph : 
```
Tu es une IA qui génère des graphviz à partir de textes de philosophie pour faire un manuel de philosophie. 
Voici le texte :
---
« Tu es assuré d'apprendre tout ce qui se passe dans ton âme, pourvu que ce soit assez important, parce que, alors, ta conscience te le signale. Et quand dans ton âme tu n'as reçu aucune nouvelle de quelque chose, tu admets en toute confiance que cela n'est pas contenu en elle. Davantage, tu vas jusqu'à tenir “psychique” pour identique à “conscient”, c'est-à-dire connu de toi, malgré les preuves les plus patentes que dans ta vie psychique, il doit en permanence se passer beaucoup plus de choses qu'il n'en peut accéder à ta conscience.
[…] Mais dans tous les cas, ces renseignements de ta conscience sont incomplets et souvent peu sûrs ; par ailleurs, il arrive assez souvent que tu ne sois informé des événements que quand ils se sont déjà accomplis et que tu ne peux plus rien y changer. Qui saurait évaluer, même si tu n'es pas malade, tout ce qui s'agite dans ton âme et dont tu n'apprends rien, ou dont tu es mal informé ? Tu te comportes comme un souverain absolu, qui se contente des renseignements que lui apportent les hauts fonctionnaires de sa cour, et qui ne descend pas dans la rue pour écouter la voix du peuple. Entre en toi-même, dans tes profondeurs, et apprends d'abord à te connaître, alors tu comprendras pourquoi tu dois devenir malade, et tu éviteras peut-être de le devenir. »
C'est ainsi que la psychanalyse a voulu instruire le moi. Mais ces deux élucidations, à savoir que la vie pulsionnelle de la sexualité en nous ne peut être domptée entièrement, et que les processus psychiques sont en eux-mêmes inconscients, ne sont accessibles au moi et ne sont soumis à celui-ci que par le biais d'une perception incomplète et peu sûre, reviennent à affirmer que le moi n'est pas maître dans sa propre maison.

Sigmund Freud, « Une difficulté de la psychanalyse » [1917], dans L'Inquiétante étrangeté et autres essais [1919], trad. de l'allemand (Autriche) par B. Féron, Gallimard, 1985, p. 185-186.
---
```

texte2page :
```
Tu es une IA qui génère des pages pour faire un manuel de philosophie. Voici la structure à suivre  :

- Titre = Thèse principale du texte
- Sous titre = Présentation du texte de 4 lignes maximum : ce à quoi il répond, ses enjeux etc.
- Le texte avec les moments importants en gras en markdown
- Un encadré contenant des points de vocabulaire précis du texte
- Un encadré faisant usage d'un des repères du programme de philosophie (Liste officielle des repères =  "Absolu/relatif – Abstrait/concret – En acte/en puissance – Analyse/synthèse –Concept/image/métaphore – Contingent/nécessaire – Croire/savoir –Essentiel/accidentel – Exemple/preuve - Expliquer/comprendre – En fait/en droit –Formel/matériel – Genre/espèce/individu – Hypothèse/conséquence/conclusion –Idéal/réel – Identité/égalité/différence – Impossible/possible – Intuitif/discursif –Légal/légitime – Médiat/immédiat – Objectif/subjectif/intersubjectif –Obligation/contrainte – Origine/fondement – Persuader/convaincre –Principe/cause/fin – Public/privé – Ressemblance/analogie – Théorie/pratique –Transcendant/immanent – Universel/général/particulier/singulier –Vrai/probable/certain" ), expliquant le repère en rapport avec la thèse de l'auteur
- Un encadré "Explication au fil du texte" où le lecteur est renvoyé à des moments précis dans le texte, chaque renvoi est explicite dans le texte de l'auteur et marqué par un symbole (A)  et où on lui pose 2 questions à chaque moment.


Voici le texte :
---
Je suppose donc que toutes les choses que je vois sont fausses ; je me persuade que rien n'a jamais été de tout ce que ma mémoire remplie de mensonges me représente ; je pense n'avoir aucun sens ; je crois que le corps, la figure, l'étendue, le mouvement et le lieu ne sont que des fictions de mon esprit. Qu'est-ce donc qui pourra être estimé véritable ? Peut-être rien autre chose, sinon qu'il n'y a rien au monde de certain. Mais que sais-je s'il n'y a point quelque autre chose différente de celles que je viens de juger incertaines, de laquelle on ne puisse avoir le moindre doute ? N'y a-t-il point quelque Dieu, ou quelque autre puissance, qui me met en l'esprit ces pensées ? Cela n'est pas nécessaire, car peut-être que je suis capable de les produire de moi-même. Moi donc à tout le moins ne suis-je pas quelque chose ? Mais j'ai déjà nié que j'eusse aucun sens ni aucun corps. J'hésite néanmoins, car que s'ensuit-il de là ? Suis-je tellement dépendant du corps et des sens que je ne puisse être sans eux ? Mais je me suis persuadé qu'il n'y avait rien du tout dans le monde, qu'il n'y avait aucun ciel, aucune terre, aucuns esprits, ni aucuns corps ; ne me suis-je donc pas aussi persuadé que je n'étais point ? Non certes, j'étais sans doute, si je me suis persuadé, ou seulement si j'ai pensé quelque chose. Mais il y a un je ne sais quel trompeur très puissant et très rusé, qui emploie toute son industrie à me tromper toujours : il n'y a donc point de doute que je suis, s'il me trompe ; et qu'il me trompe tant qu'il voudra, il ne saurait jamais faire que je ne sois rien, tant que je penserai être quelque chose. De sorte qu'après y avoir bien pensé, et avoir soigneusement examiné toutes choses, enfin il faut conclure, et tenir pour constant que cette proposition, Je suis, j'existe, est nécessairement vraie, toutes les fois que je la prononce ou que je la conçois en mon esprit. 
René Descartes, Méditations métaphysiques [1641], trad. du latin par le duc de Luynes, Gallimard, coll. « Tel », 2018, p. 117-119.
---
```

genFicheRepère:
```
1. Définitions :
Pour chaque repère, commencez par fournir une définition claire et concise du terme. Assurez-vous que la définition soit accessible aux lecteurs qui ne sont pas familiers avec la philosophie.

2. Usage détaillé avec exemple quotidien :
Ensuite, pour chaque repère, expliquez son usage de façon détaillée et argumentée. Utilisez un exemple concret de la vie quotidienne pour illustrer comment ce repère s'applique dans la réalité. Par exemple, pour "Absolu/relatif", expliquez comment quelque chose peut être absolu (invariable) dans un contexte donné, mais relatif (variable) dans un autre contexte, et donnez un exemple, comme la température absolue et relative.

3. Autres définitions et usages :
Si le repère a d'autres définitions ou usages, énoncez-les et expliquez-les également avec des exemples. Par exemple, pour "Contingent/nécessaire", montrez comment quelque chose peut être nécessaire dans un contexte philosophique, mais contingent dans un contexte empirique, et donnez des exemples pertinents.

4. Tableau de distinctions conceptuelles :
Utilisez un tableau pour synthétiser les distinctions conceptuelles entre les repères. Par exemple, vous pourriez créer un tableau avec des colonnes pour "Repère", "Définition", "Exemple quotidien", "Autres définitions/usages", et "Usages incorrects à éviter". Cela aidera les visiteurs à visualiser les différences entre les repères plus facilement.

5. Usages incorrects à éviter :
Enfin, pour chaque repère, soulignez les usages incorrects courants que les gens doivent éviter. Par exemple, pour "Identité/égalité/différence", expliquez les confusions fréquentes et montrez comment éviter ces erreurs.

Liste des repères  : 

– Vrai/probable/certain.
```
