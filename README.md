# Régression polynomiale

Cette fois on crée une regression polynomiale avec PyTorch.

On récupère la même logique qu'avec la regression linéaire, à la différence que la génération de nos données donnent un nuage de points plus incurvé.

Par conséquent, on crée une matrice x qui récupère le vecteur square_meters et le met au carré, et on lui accole square_meters.

Bien évidemment on modifie le modèle linéaire.

Aussi, j'ai ajouté un graphe pour étudier l'évolution de la loss, et ainsi pouvoir ajuster plus facilement les hyper-paramètres. 

