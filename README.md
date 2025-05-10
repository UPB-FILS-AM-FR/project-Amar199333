Détecteur d'humidité du sol avec Arduino
Description
Ce projet a pour objectif de concevoir un système de détection d'humidité du sol 'utilisant une carte Arduino et un capteur d'humidité. Le système permet de mesurer en temps réel le niveau d'humidité d'un sol et de déclencher une alerte (LED, buzzer) si celui-ci devient trop sec. Ce dispositif est utile pour éviter un arrosage excessif ou insuffisant des plantes
 Motivation
L'entretien régulier des plantes nécessite un arrosage adapté à leurs besoins Or,il est souvent difficile de s avoir quand le sol est suffisamment humide. Ce projet vise à automatiser la surveillance de l'humidité du sol afin de simplifier cette tâche, économiser de l'eau et améliorer la santé des plantes. C'est également un excellent projet pédagogique pour apprendre les bases de l'électronique et de la programmation avec Arduino
 Architecture du système
1. **Capteur d'humidité du sol**: Mesure la teneur en eau du sol et envoie une valeur analogique à l'Arduino 2. **Carte Arduino**: Lit la valeur du capteur, la traite, et déclenche une action si nécessaire. 3. **LED**: S'allume pour signaler que le sol est trop sec (valeur seuil personnalisable). 4. **Buzzer (optionnel)**: Émet un son d'alerte si le sol est sec, 5. **Écran LCD (optionnel)**: Affiche en temps réel la valeur de l'humidité. 6. *Pompe à eau (optionnelle)**: Peut être activée automatiquement pour arroser les plantes
 Matériel utilisé :
Arduino Uno, Capteur d'humidité du sol, Résistance 10kQ, LED rouge, Résistance 2200, Câbles Dupont, Breadboard, Alimentation Arduino, Écran LCD I2C (optionnel), Buzzer (optionnel), Mini pompe à eau (optionne
