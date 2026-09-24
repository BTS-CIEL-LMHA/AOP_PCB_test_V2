Ce PCB a été crée pour expérimenter sur différents montage d'amplificateurs opérationnels.

Le principe est d'utiliser 2 cavaliers pour sélectionner le montage utilisé : un pour l'entrée, l'autre pour la sortie.

2 cavaliers à l'entrée et à la sortie permettent de court-circuiter le condensateur de liaison

ATTENTION : il ne faut pas avoir plusieurs cavaliers sur des sorties au risque de court circuit et de destruction des AOP

(on peut avoir plusieurs cavaliers sur les entrées mais c'est déconseillé et cela peut créer des effets indésirables : injection de tension d'un montage à l'autre)


REMARQUE : Les amplis inverseurs et les filtres passe-haut et passe-bande ne sont pas utilisables car l'entrée + est reliée directement ou par une résistance à la masse (au lieu du point milieu de l'alimentation = masse virtuelle)

Les amplis non inverseurs sont utilisable à condition d'avoir un offset (1/2 alimentation) sur le signal d'entrée.

Il est possible assez facilement de modifier les filtres passe-haut et passe-bande en remplaçant la résistance qui va vers la masse par une résistance qui va vers une masse virtuelle.

Pour les amplis inverseur la connexion à la masse étant directe la modification est plus complexe (couper la connexion à la masse du PCB et installer un fil vers la masse virtuelle).
