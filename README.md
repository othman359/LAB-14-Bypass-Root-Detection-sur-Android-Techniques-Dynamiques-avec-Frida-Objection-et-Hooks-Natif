# LAB-14-Bypass-Root-Detection-sur-Android-Techniques-Dynamiques-avec-Frida-Objection-et-Hooks-Natif
Étape 1 — Préparer l’environnement (débutant) 
Cette étape permet de vérifier que ton PC est bien connecté à l’émulateur Android via Frida.
Si tout fonctionne, tu verras la liste des applications ou processus en cours sur l’appareil.
Sinon, cela signifie qu’il y a un problème de connexion ou que frida-server n’est pas lancé sur l’émulateur.
<img width="1344" height="756" alt="image" src="https://github.com/user-attachments/assets/2f5052fa-690f-4381-b57c-f40a1c731b3a" />

Étape 2 — Démarrer frida-server sur l’appareil (indispensable pour Frida/Objection/Medusa)
Ici, tu démarres l’application DIVA (Damn Insecure and Vulnerable App) sur l’émulateur.
Cela permet de créer le processus de l’application, que Frida pourra ensuite intercepter et analyser.
<img width="1919" height="664" alt="image" src="https://github.com/user-attachments/assets/22a5cf41-a905-4d40-b2a7-6636a7ee98b1" />

 Étape 3 — Frida: comprendre en 10 minutes :
 Cette étape sert à confirmer que l’application est bien active et que son processus est détectable.C’est important car Frida ne peut s’attacher qu’à un processus qui est réellement en cours d’exécution.
 <img width="1318" height="285" alt="image" src="https://github.com/user-attachments/assets/2b24ecef-2a5d-475d-a70f-201d395947ab" />






