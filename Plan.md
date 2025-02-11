
<!--  #region  -->

% \section*{Remerciements}

% \section*{Abstract}

% \section*{Résumé}

% \section{Introduction}
% \subsection{Keskispass dans l'espace}
% \subsubsection{Dose}
% \paragraph{Dose Exemple}
% \subparagraph{Les diverses unités (rad, gray, Sv, saucisse)}
% \paragraph{Dose Impact on IC}
% \subparagraph{VTh (TID)}
% \subsection{Débit de Dose}
% \paragraph{Dose Rate Effet}
% \paragraph{Dose Impact}
% \subparagraph{SingleUppsetEvent}
% \subparagraph{Génération Photocourant}

% \section{Devenir Robuste}
% \subsection{Avanguarde}
% \paragraph{Choix Techno}
% \subparagraph{28 FDSOI}
% \paragraph{Choix Design}
% \subparagraph{Theshold Voltage Low Dependency}
% \paragraph{Choix Layout}
% \subparagraph{Réduction Résistance}
% \subparagraph{Guard Ring}
% \subparagraph{Réduction Taille Jonction PN}
% \subparagraph{Éloignement Taille Jonction PN}
% \subsection{Simulation Setup}
% \paragraph{Cadence}
% \paragraph{Model Diode Douteux}
% \paragraph{Pose de Géné de Courrant Partout}
% \subsection{Experimental Setup}
% \paragraph{LP2i \& Carmelec (\& CEA Inshallah) Particule Accelerator}
% \paragraph{DIL24 "Tapped"}
% \subparagraph{Radiation}
% \subparagraph{Pas de RF}
% \subparagraph{Facile Radiation}
% \paragraph{Pas de Kapton pour être sous Vide}

% \section{Mes Circuits}
% \paragraph{Layout Technics (T, LBTR, LBTR+T3)}
% \paragraph{Pas d'Instance ESD}
% \paragraph{Erreur Gate Antenna}
% \subparagraph{Source}
% \subparagraph{Bridging}
% \subparagraph{Diodes}
% \subparagraph{Source}
% \subparagraph{Diode Robuste aux Radiations}
% \paragraph{Buphagus \& Inshallah : Vref}
% \subparagraph{State of the Art}
% \subparagraph{How to Design a Voltage Reference}
% \subparagraph{Buphagus = Méga Radiation}
% \subparagraph{Buphagus = AVIC}
% \subparagraph{Inshallah = Méga Ref de Tension mais Back Gate qui Génére des Courants}
% \subparagraph{Inshallah = ICECS}
% \subparagraph{Buphagus = ICECS Diode}
% \subparagraph{Mesures}
% \paragraph{Inshallah : AOP Supplie Sensing de Justine Guedey, TCAS2}
% \subparagraph{Oscillateur}
% \subparagraph{3 Version de l'AOP}
% \paragraph{Global}
% \paragraph{Hiroshi}

% \section{Limitations de l'Étude}

% \section{Conclusion}
% \paragraph{Résumé des Principaux Résultats}
% \paragraph{Perspectives pour les Travaux Futurs}
% \paragraph{Recommandations}

% \section{Références}
% \paragraph{Liste des Sources Citées}


<!--  #endregion -->




# Remerciment

Abstract
Résumé


1 - keskispass dans l'espace, 
        dose
                dose exemple
                         les diverses unitées (rad, gray, Sv, saucisse)
                dose impact on IC
                        VTh (TID)
        debit de dose
                dose rate effet
                dose impact
                        SingleUppsetEvent
                        génération photocourant

                jonction pn = générateur de courants
                silicium = générateur de courants aussi mais les e-/h+ se régénérent plus simplement alors que dans les jpn ca fait un toboogan
                        ELDRS = Enhanced Low Dose Rate Sensitivity => des courrants sont générés par les radiations dans le silicium mais sans les jonctions pn, mais les debits sont trop faibles pour considérer le debit de dose par rapport à la dose
                        


2 - Devenir robuste
        1 - avanguarde
                choix techno
                        28 FDSOI vs bulk (dose et debit de dose)
                choix design
                        theshold voltage low dependency
                choix layout
                        réduction résistance
                                guard ring
                        reduction taill jonction PN
                                gaurd ring
                        éloignement taille jounction PN
        2 - simulation setup
                cadence
                model diode douteux
                pose de géné de courrant partout
        3 - experimental setup
                LP2i & carmelec (& CEA inshallah) particule accelerator
                DIL24 "tapped"  => radiation 
                                => pas de RF
                                => facile radiation
                pas de kapton pour être sous vide


3 - Mes circuits
        
        Buphagus : pas perfomant mais design orienté vers la robustesse dose et debit de dose
        layout technics (T, LBTR, LBTR+T3)
        pas d'instance ESD
        Erreur gate antenna
                source
                bridging
                diodes
                        source
                diode robuste aux radiations
        PCB Buphagus
                pas de diode
                piste simple
                PCB en forme de platine pour les radiations
                capa de découplage et ESD
                pas de capton ni de capa organique vous la mise sous vide
 

        Buphagus & Inshallah : Vref
                state of the art
                how to design a voltage reference
                        buphagus =  méga radiation
                        buphagus = AVIC
                        inshallah = méga ref de tension mais back gate qui génére des courants
                        inshallah = ICECS
                        Buphagus = ICECS diode
                                mesures...

        Inshallah : AOP supplie sensing de Justine Guedey, TCAS2
                oscillateur
                3 version de l'AOP
                3 version de la reference de tension, design pas robuste, que le layout => creation d'une méthode de durcissement

        Global....
        Hiroshi...

limitations de l'étude

5 - Conclusion
        résumé des principaux résultats
        perspectives pour les travaux futurs
        recommandations

6 - Références
        liste des sources citées
        