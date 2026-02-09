# WEB-CLIENTS-2

## Description 
 Site web de gestion d' une playlist YouTube avec ajout/édition/suppression validés, lecteur autoplay intégré, durée totale auto-calculée et favoris. 

## Fonctionnalitées

| Fonctionnalité        | Description                                             |
| --------------------- | ------------------------------------------------------- | 
| Ajouter vidéo         | Formulaire validé (nom, URL YT, durée hh:mm:ss, favori) | 
| Lecteur intégré       | Clic bouton →  YouTube autoplay                         |              
| Édition rapide        | Bouton éditer → pré-remplit formulaire                  |              
| Suppression sécurisée | Confirmation + refresh total                            |              
| Favoris               | Icône visuelle (étoile)                                 |              
| Durée totale          | Calcul auto hh:mm:ss toutes vidéos                      | 
| Validation            |  URL YouTube stricte                                    | 
| Responsive            | Bootstrap + mobile-first                                | 
| Persistance           | localStorage (sauvegarde auto)                          |

## Problemes

| Probleme                                       | Impact                      | 
| ---------------------------------------------- | --------------------------- |
| Données perdues au refresh                     | Playlist vide après F5      |
| Checkbox non validée côté client               | État favori perdu           |
| Retourne list<T> au lieu d'un élément          | Non conforme spec examen    |
| get_nombre_contact() incrémente à chaque appel | Compteur faux (x10)         |
| return false dans boucle for                   | Ne vérifie que 1er élément  |
| ajouter_contact(Contact) non implémentée       | 50% fonctionnalités perdues |
| Données vidéos non sauvées                     | Perte playlist refresh      |


--------------------------------------------------------------------------------------
CONÇU LE 01 MAI 2025 - 21 MAI 2025
