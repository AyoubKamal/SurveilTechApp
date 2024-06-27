
#  SurveilTech :

Une application mobile Android , capable de scanner les réseaux Wi-Fi pour identifier les appareils IoT présents et potentiellement utilisés pour des activités de surveillance ou étant vulnérables. Elle permet de prendre des mesures proactives pour sécuriser l'environnement numérique de l'utilisateur .
#

Pour notre application, on mets en place 2 méthodes. On recommande vivement la première méthode qui fera un scan précis du réseau. La second utilisant l'émulateur, tous les appareils du réseau ne seront pas détectés

## Installation et simulation : 

Pour simuler notre application, nous avons choisi 2 méthodes simples. Étant donné que tout le monde ne dispose pas d'Android Studio et que la configuration des paramètres de Gradle peut prendre du temps et peut être compliqué, nous avons décidé de fournir l'APK (Android Package Kit) de l'application. 

*Il faut utiliser cet application uniquement dans un réseau domestique.*

#
## Méthode 1 -  Avec téléphone Android physique :
#### Voici les étapes à suivre pour pouvoir installer notre application sur un téléphone : 

- Pour avoir le meilleur résultat, utiliser un téléphone avec une version d'Android inférieure ou égale à 10.
- Transférer le fichier APK sur votre téléphone via USB. Il peut être stocké dans la mémoire interne ou la mémoire externe de votre appareil Android.
- Ouvrir le gestionnaire de fichiers de l’appareil Android pour localiser l’APK. On l'appelle généralement : "mes fichiers" ou "Navigateur de fichiers", et on le trouve généralement dans le tiroir de l'application.
- Sur l'appareil Android, appuyer sur le fichier APK qui vient d'être copié, il vous demandera si vous souhaitez installer l'application, confirmez simplement et continuez, une fois terminé, appuyer sur le bouton « Terminé » et la nouvelle application est prête à être utilisée.

## Méthode 2 - Sans téléphone Android physique :
##
#### Remarque : 
##
Dans cette situation, si vous n'avez pas de téléphone Android physique, il est possible d'utiliser un émulateur pour simuler le fonctionnement de l'application. Cependant, vous ne serez pas en mesure de détecter les appareils IoT réels connectés à votre réseau, ni d'identifier les ports ouverts. En effet, l'émulateur est un environnement virtuel qui n'existe pas réellement dans le réseau physique. Ce qu'il affichera, ce sont des appareils de simulation présents dans l'environnement virtuel, et non dans l'environnement physique, avec des adresses IP virtuelles du type 10.0.2.x. Malheureusement, vous ne pourrez détecter les ports ouverts que sur un ou deux de ces appareils, et donc, les recommandations ne concerneront que ces derniers.

##
#### Voici les étapes à suivre pour pouvoir simuler notre application avec un émulateur en ligne : 
###

- Télecharger le fichier apk de l'application que vous trouveez ci-joint dans le dépot du projet .

- Visitez le site emulateur des apk sur android : https://www.myandroid.org/android-manager-to-run-apk-online/

- Appuyer sur la petite icon d'android que vous trouvez devant vous pour vous dériger vers l'interface de l'emulateur d'apk .
- Charger le fichier apk que vous avez télecharger au début de l'installation. Cliquer sur "Click the bottom to Upload an APK to be run with our emulator"
- Appuyer sur Run Apk pour vous diriger à l'interface de simulation
- Vous attendez 10 secondes pour le boot ensuite vous appuyez sur "Entrer"

### Recommandations

- Il faut cliquer sur le bouton "Recommandation" pour qu'elles s'affichent.
- Il faut attendre que les ports d'affiches pour avoir les meilleurs recommandations pour l'appareil concerné.
