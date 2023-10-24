## Travaux Récents

<div align="center">
    <table align="center">
        <tr>
            <td width="33%">
                <a href="https://sites.google.com/view/relmm">
                    <h4>Apprentissage par renforcement autonome en conditions réelles</h4>
                    <img width="100%" src="/assets/projects/ReLMM/complex_room_short.gif">
                </a>
            </td>
            <td width="66%">
                Nous étudions comment les robots peuvent apprendre de manière autonome des compétences nécessitant à la fois la navigation et la préhension. Bien que l'apprentissage par renforcement permette en principe l'apprentissage automatisé des compétences robotiques, dans la pratique, l'apprentissage par renforcement dans le monde réel est complexe et nécessite souvent une instrumentation et une supervision importantes. Notre objectif est de concevoir un système d'apprentissage par renforcement robotique pour apprendre la navigation et la manipulation ensemble, de manière autonome et sans intervention humaine, permettant un apprentissage continu dans des conditions réalistes. Notre système proposé, ReLMM, peut apprendre en continu sur une plateforme du monde réel sans instrumentation environnementale, sans intervention humaine et sans accès à des informations privilégiées, telles que des cartes, des positions d'objets ou une vue globale de l'environnement. Notre méthode utilise une politique modularisée avec des composants pour la manipulation et la navigation, où l'incertitude de la politique de manipulation guide l'exploration pour le contrôleur de navigation, et le module de manipulation fournit des récompenses pour la navigation. Nous évaluons notre méthode sur une tâche de nettoyage de pièce, où le robot doit se déplacer et ramasser des objets dispersés sur le sol. Après une phase d'entraînement de curriculum de préhension, ReLMM peut apprendre la navigation et la préhension ensemble de manière entièrement automatique, en environ 40 heures d'entraînement autonome en conditions réelles.

            </td>
        </tr>
    </table>
</div>

<div align="center">
    <table align="center">
        <tr>
            <td width="33%">
                <a href="https://arxiv.org/abs/2104.11707">
                    <h4>Généralisation entre robots par inférence de la morphologie</h4>
                    <img width="100%" src="/assets/projects/anymorph/anymorph_prompt.gif">
                </a>
            </td>
            <td width="66%">
                L'approche prototypique de l'apprentissage par renforcement consiste à former des politiques adaptées à un agent particulier à partir de zéro pour chaque nouvelle morphologie. Les travaux récents visent à éliminer la rétroaction des politiques en examinant si une politique agnostique à la morphologie, formée sur un ensemble diversifié d'agents ayant des objectifs de tâche similaires, peut être transférée à de nouveaux agents ayant des morphologies inconnues sans rétroformation. Il s'agit d'un problème complexe qui a nécessité que les approches précédentes utilisent des descriptions de la morphologie du nouvel agent préalablement conçues. Au lieu de concevoir manuellement cette description, nous proposons une méthode basée sur les données qui apprend une représentation de la morphologie directement à partir de l'objectif de l'apprentissage par renforcement. Notre approche est le premier algorithme d'apprentissage par renforcement capable de former une politique capable de se généraliser à de nouvelles morphologies d'agent sans nécessiter une description préalable de la morphologie de l'agent. Nous évaluons notre approche sur la référence standard pour le contrôle agnostique de l'agent et améliorons l'état actuel de l'art en généralisation sans formation préalable à de nouveaux agents. Importamment, notre méthode atteint de bonnes performances sans description explicite de la morphologie.

            </td>
        </tr>
    </table>
</div>

<div align="center">
    <table align="center">
        <tr>
            <td width="33%">
                <a href="https://sites.google.com/view/surpriseminimization">
                    <h4>Minimisation de l'entropie pour des comportements émergents</h4>
                    <img width="100%" src="/assets/projects/SMiRL/robotsurprise_stacked.png">
                    <img width="100%" src="/assets/projects/SMiRL/miniGrid/minigrid-maze-random-count.gif">
                </a>
            </td>
            <td width="66%">
                Tous les organismes vivants définissent des niches environnementales dans lesquelles ils peuvent maintenir une prédictibilité relative au milieu de l'entropie croissante qui les entoure [schneider1994, friston2009]. Les êtres humains, par exemple, font de grands efforts pour se protéger de la surprise : nous nous regroupons par millions pour construire des villes avec des maisons, fournissant de l'eau, de la nourriture, du gaz et de l'électricité pour contrôler la détérioration de nos corps et de nos espaces de vie face à la chaleur et au froid, au vent et à la tempête. Le besoin de découvrir et de maintenir de tels équilibres sans surprise a suscité beaucoup d'ingéniosité et d'habileté chez les organismes dans des habitats naturels très divers. Motivés par cela, nous nous demandons si le désir de préserver l'ordre au milieu du chaos pourrait guider l'acquisition automatique de comportements utiles chez les agents artificiels.

            </td>
        </tr>
    </table>
</div>
