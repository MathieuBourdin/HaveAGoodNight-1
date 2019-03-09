# HaveAGoodNight
Projet Data Viz : HaveAGoodNight


Participants : BESSIS Victor

	       BOURDIN Mathieu
	       
	       MIZRAHI Guilhem
	       
			   
Desciption du projet :


L'ambition de notre projet était d'utiliser la visulaisation de données afin d'expliciter les liens entre temps de sommeil, heures de cours et fatigue.

Pour cela, nous avons récupéré manuellement les données suivantes pour les 3 membres du projet entre le 18 janvier et le 8 février 2019:

    - Heure de coucher
    - Heure de réveil
    - Temps de sommeil
    - Heure du premier cours
    - Heure du dernier cours
    - Nombre d'heures de cours en théorie
    - Nombre d'heures de cours en pratique
    - Heure de retour au foyer
    - Etat de fatigue (entre 1 = peu fatigué et 5 = très fatigué)
    - Remarques


Visualisations/Conclusions


Notre site : https://g-mizrahi.github.io/HaveAGoodNight/index.html


Visualisation 1 : https://g-mizrahi.github.io/HaveAGoodNight/vis1.html


L'idée de cette visualisation est de réprésenter en fonction du temps au choix :

		- Le temps de sommeil
		
		- Les heures de coucher
		
		- Les heures de lever
		
		- L'état de fatigue
		
		
Cette visualisation ne permet pas de montrer de lien entre les différents critères, mais permet de comparer les données obtenues pour les différents individus.

Ce graphique a été réalisé en s'inspirant de l'architecture du code suivant :
https://bl.ocks.org/ProQuestionAsker/8382f70af7f4a7355827c6dc4ee8817d

Les différents constats que permet de tirer cette visualisation sont les suivants: *
- les trois individus étudiés ont tous les trois des rythmes de sommeil très distints les uns des autres et sont tous les trois en moyenne légèrement en-dessous de la barre des 8 heures de sommeil par nuit conseillées (environ 7 heures et demi en moyenne). 
- pour chaque individu, les données récoltées sont très irrégulières quelque soit la donnée affichée (heure de coucher, heure de lever, temps de sommeil ou état de fatigue). Des pics et des creux sont visibles sur les graphes, les nuits ne sont pas du tout régulières.
- plusieurs comportements particuliers sont  visibles sur les courbes, comme la présence d'un weekend d'étage pour l'individu bleu foncé ou de cours à 8 heures lorsque les individus se lèvent à 7 heures (ce qui est globalement sous leur comportement habituel).
- les heures de coucher se situent globalement entre minuit et deux heures du matin ; les heures de lever se situent globalement entre 7 heures et 10 heures.
- l'individu bleu foncé est celui qui a les heures de coucher les plus tardives tandis que l'individu orange est celui qui a les nuits les plus courtes.


Visualisation 2 : https://g-mizrahi.github.io/HaveAGoodNight/vis2.html


Ici nous visualisons l'emploi du temps de chaque sujet. 

On remarque qu'il n'y a pas beaucoup de cours en 3A.

Cette remarque est à coupler avec une remarque que nous nous sommes faite : nous n'avons jamais eu aussi peu cours à Centrale, mais nous n'avons jamais autant travaillé.

Il aurait alors été interessant de noter aussi les heures de travail personnel en dehors des cours.


Visulaisation 3 : https://g-mizrahi.github.io/HaveAGoodNight/vis3.html


Ici on met en évidence le lien entre fatigue et temps de sommeil.

Nous nous attendions à avoir un taux de fatigue inversement proportionnel au temps de sommeil.

Cependant, nous avons remarqué que certains points correspondent à une durée de sommeil de 5h mais un état de fatigue de 1.

Ceci s'explique par le fait que nous dormons peu uniquement lorsque nous n'avons pas d'événement important le lendemain, ce qui explique pourquoi nous ne ressentons pas forcément la fatigue.

Il est important de noter que la mesure de l'état de fatigue est la plus imprécise : le ressenti de la fatigue changeant entre individus et selon le moment de la journée.
