# 🏡 Home Assistant – Collection de Blueprints Personnalisés

Bienvenue dans ma collection de **blueprints Home Assistant**, conçus pour simplifier votre quotidien, renforcer votre confort et automatiser intelligemment votre maison.
Chaque blueprint répond à un besoin concret : gestion de l'énergie, sécurité, éclairage, jardin, notifications… tout pour rendre votre smart home plus intuitive.

---

## 📦 Liste des Blueprints

### 🔋 Batterie & Énergie

#### **batterie_tado.yaml**
Surveille automatiquement l'état des piles de vos appareils Tado et vous alerte lorsqu'elles deviennent faibles.
Une solution simple pour éviter les pannes de chauffage ou de climatisation au mauvais moment.

#### **notification_on_low_battery.yaml**
Envoie régulièrement une notification lorsque la batterie d'un appareil Home Assistant est faible ou vide.
Idéal pour garder un œil sur l'ensemble de vos capteurs sans devoir les vérifier un par un.

#### **Reboot-HA-weekly.yaml**
Effectue un redémarrage hebdomadaire automatique de l'hôte Home Assistant pour maintenir les performances optimales.

---

### 🌿 Jardin & Extérieur

#### **check_if_garden_should_be_watered.yaml**
Analyse les conditions météo, l'humidité et d'autres paramètres pour déterminer si votre jardin a réellement besoin d'être arrosé.
Un blueprint pensé pour économiser l'eau tout en gardant vos plantes en pleine santé.

---

### 📸 Sécurité & Surveillance

#### **frigate_notification_by_telegram.yaml**
Envoie automatiquement une photo et une vidéo via Telegram lorsqu'un objet est détecté par Frigate.
Une manière efficace de rester informé en temps réel de ce qui se passe autour de votre maison.

#### **notify_on_door_or_windows_change.yaml**
Recevez une notification dès qu'une porte ou une fenêtre change d'état.
Parfait pour la sécurité, mais aussi pour éviter de chauffer inutilement une pièce ouverte.

---

### 🪟 Confort & Ventilation

#### **notify_on_indoor_outdoor_change.yaml**
Compare les températures intérieure et extérieure et vous avertit lorsqu'il est judicieux d'aérer ou de fermer les fenêtres.
Un petit coup de pouce pour optimiser votre confort et réduire votre consommation énergétique.

---

### 🌞 Gestion du Soleil & Confort Thermique

#### **sun_protection.yaml**
Ajuste automatiquement la position de vos volets en fonction de la position du soleil.
Protégez votre intérieur de la chaleur en été ou maximisez la lumière naturelle en hiver.

#### **sunset_actions.yaml**
Contrôle les lumières et interrupteurs en fonction de la position du soleil et de la présence détectée.
Offre un contrôle flexible et intelligent de l'ambiance de votre maison.

---

### 💡 Éclairage Intelligent

#### **toggle_light_on_presence_and_various_conditions.yaml**
Allume ou éteint une lumière en fonction de la présence et d'autres conditions (luminosité, horaire, etc.).
Un éclairage vraiment intelligent, adapté à votre mode de vie.

#### **toggle_light_when_other_light_or_switch_state_change.yaml**
Synchronise une lumière avec l'état d'une autre lumière ou d'un interrupteur.
Idéal pour créer des groupes d'éclairage ou des comportements cohérents dans une pièce.

#### **ikea_rodret_z2m_v2.yaml**
Contrôle des lumières avec la télécommande IKEA RODRET (E2201) via Zigbee2MQTT.
Permet d'allumer/éteindre et de régler la luminosité.

#### **ikea_styrbar_z2m_v2.yaml**
Contrôle des lumières avec la télécommande IKEA STYRBAR (E2001/E2002) via Zigbee2MQTT.
Permet de contrôler la luminosité et la température de couleur.

#### **sonoff_snzp-01p.yaml**
Contrôle des lumières avec le bouton SONOFF SNZP-01P via Zigbee2MQTT.
Appui simple ou double pour différentes actions.

---

### 🔧 Contrôles Zigbee2MQTT

#### **tuya_ts0041_z2m_v2.yaml**
Contrôle des actions avec Tuya TS0041 via Zigbee2MQTT.
Appui simple, double ou maintenu pour déclencher des actions personnalisées.

#### **tuya_ts0043_z2m_v2.yaml**
Contrôle des actions avec Tuya TS0043 via Zigbee2MQTT.
3 boutons avec appui simple, double ou maintenu pour chaque bouton.

---

### 🗑️ Notifications & Vie Quotidienne

#### **notification_customized_of_waste_collections.yaml**
Notifications personnalisées pour les collectes de déchets via RecycleApp.
Annonce les collectes du lendemain via Telegram, Alexa et media players.

#### **tags_project.yaml**
Blueprint d'exemple pour la sélection de tags multiples.
Démontre l'utilisation des tags dans les automatisations Home Assistant.

---

## 🚀 Installation

1. Copiez le contenu du blueprint souhaité depuis ce dépôt
2. Dans Home Assistant, allez dans **Paramètres > Automatisations & Scènes > Blueprints**
3. Cliquez sur **Importer un blueprint**
4. Collez le contenu YAML et validez
5. Créez une nouvelle automatisation basée sur ce blueprint
6. Configurez les paramètres selon vos besoins

## 🤝 Contribution

Les contributions sont les bienvenues ! Si vous avez des idées d'améliorations ou de nouveaux blueprints, n'hésitez pas à ouvrir une issue ou une pull request.

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

---

*Dernière mise à jour : Mars 2026*
