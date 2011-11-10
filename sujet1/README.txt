A PROPOS :
    Cette application a �t� r�alis�e dans le cadre d'un projet de SSII
(Son, Signal et Image pour l'Informaticien) � l'�cole d'ing�nieurs
Polytech'Nice - Sophia Antipolis.

    Elle permet de trouver la fr�quence de sous �chantillonnage 
permettant d��couter une version comprim�e d�un signal haute fid�lit� 
sans le d�grader de mani�re excessive en 3 �tapes :

    - analyse du contenu du spectre et du spectrogramme du signal 
      pour trouver la nouvelle fr�quence d��chantillonnage ;
    - filtrage avec un filtre passe bas ;
    - r�-�chantillonnage et reconstruction � la fr�quence 
      d��chantillonnage initiale gr�ce au filtre passe-bas 
      utilis� comme filtre interpolateur.


AUTEURS :
    Guy CHAMPOLION (champoll@polytech.unice.fr)
    Fran�ois CHAPUIS (fchapuis@polytech.unice.fr)


INSTALLATION :
    Pour que cette application fonctionne, vous devez 
avoir install� sur votre ordinateur la version 2.6
(ou 2.7) de Python ainsi que les biblioth�ques suivantes
dont vous trouverez les installeurs dans le dossier "libs":

    - numpy (v 1.5.1)
    - scipy (v 0.8.0)
    - matplotlib (v 1.0.0)

  Vous trouverez des informations sur le r�le jou� par ces
biblioth�ques � cette adresse :
http://www.scipy.org/Getting_Started#head-29c5ff005c7f21eb9e5e19c850159cdfd80a39ed