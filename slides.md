---
theme: apple-basic 
class: 'text-center' 
highlighter: shiki 
info: |
## Introduction à PHP
---

# Introduction à PHP : Vous y interesserez-vous ?

<div class="pt-12 flex flex-row space-x-70">
    <ol class="w-60 relative block flex flex-col space-y-8 text-left">
        <li class="text-xl"><h2>1. Origines</h2></li>
        <li class="text-xl"><h2>2. Évolution</h2></li>
        <li class="text-xl"><h2>3. Aujourd'hui</h2></li>
        <li class="text-xl"><h2>4. PHP et vous</h2></li>
    </ol>
    <img class="" src="/assets/images/1/php_pachyderme.png" alt="php-pachyderme">
</div>
<a class="relative inset-y-30 inset-x-84 text-green-300 opacity-50" href="https://www.linkedin.com/in/snitpro/">Par Sébastien NOBOUR</a>

---

## Les origines de PHP : la v1, PHP/FI 

<div class="page__origines pt-12 flex flex-row space-x-70">
    <ol class="w-60 relative block flex flex-col space-y-6 text-left">
        <li class="text-xl"><h3>Créé par Rasmus Lerdorf en 1994, à ses 26 ans</h3></li>
        <li class="text-xl" v-click="1">
            <h3>Bibliothèque logicielle en C personnelle, rendue publique et open source en 1995</h3>
        </li>
        <li class="text-xl" v-click="2">
            <h3 class="text-yellow-400">
                Pour développer des pages web dynamiques plus rapidement qu'avec Common Global Interface
            </h3>
        </li>
        <li class="text-xl relative bottom-35 bg-black h-40" v-click="3">
            <h3 class="text-green-400">
                Pour conserver une trace des visiteurs qui venaient consulter son CV en 1994
                (Personal Home Page Tools/Form Interpreter) 
            </h3>
        </li>
    </ol>
    <div class="flex flex-col space-y-4">
        <img class="w-40 h-40" src="/assets/images/1/rasmus.jpeg" alt="Rasmus Lerdorf">
        <a href="https://twitter.com/rasmus" target="_blank" class=" 
            text-xl text-light-blue-500"
        >
            <carbon-logo-twitter />@rasmus
        </a>
    </div>
</div>

<!--
né 22 novembre 1968 au Groenland, 
nationalité danois canadien
Ingénieur système

produire des pages web dynamiques plus rapidement qu’avec d’autres langages comme Perl-CGI ( remplir page web de données reçues d’un serveur web distant) 
-->

---

## L'évolution de PHP : la v2 et v3

<div class="page__evolution--v2 pt-12 flex flex-row space-x-70">
    <ol class="w-60 relative block flex flex-col space-y-6 text-left">
        <li class="text-xl"><h3>PHP/VI v2 sortie en 1996, mais impopulaire</h3></li>
        <li class="text-xl" v-click="2">
            <h3>
                Redéveloppent du cœur de PHP/FI v2 par Andi Gutmans et Zeev Suraski, avec Rasmus Lerdorf.
            </h3>
        </li>
        <li class="text-xl" v-click="3">
            <h3>En 1997, PHP v3 (Hypertext Preprocessor) est publié.</h3> 
        </li>
    </ol>
    <div class="flex flex-col space-y-4" v-click="1">
        <section class="section__andy">
            <img class="w-20 h-20" src="/assets/images/2/andi-gutmans.jpeg" alt="Andi Gutmans">
            <a href="https://twitter.com/andigutmans" target="_blank" 
                class="text-xl text-light-blue-500"
            >
                <carbon-logo-twitter />@andigutmans Andi Gutmans
            </a>
        </section>
        <section class="section__zeev">
            <img class="w-20 h-20" src="/assets/images/2/zeev-suraski.jpeg" alt="Zeev Suraski">
            <a href="https://twitter.com/zeevs" target="_blank" alt="twitter de Zeev Suraski" 
                class="text-xl text-light-blue-500"
            >
                <carbon-logo-twitter />@zeevs Zeev Suraski
            </a>
        </section>
    </div>
</div>

<!--
    v3: Ajout d'interfaces pour de multiples bases de données, protocoles et API, la facilité d'extension du langage, OOP
-->

---

## L'évolution de PHP : la Zend Engine et la v4

<div class="page__evolution--v4 pt-12 flex flex-row space-x-30">
    <ol class="w-90 relative block flex flex-col space-y-6 text-left">
        <li class="text-xl"><h3>1998, développent d'un nouveau moteur, appelé Zend Engine servant de base à PHP v4</h3></li>
        <li class="text-xl" v-click="1">
            <h3>un des langages les plus utilisés dans le développement web</h3> 
        </li>
        <li class="text-xl" v-click="2">
            <h3>
                Plein d'outils de développement basés sur PHP apparaissent.
            </h3>
        </li>
    </ol>
    <div class="flex flex-wrap" v-after="2">
        <section class="section__cms flex flex-row space-x-6">
            <img class="w-16 h-16 flex-shrink-0" src="/assets/images/2/drupal.png" alt="drupal logo">
            <img class="w-16 h-16 flex-shrink-0" src="/assets/images/2/wordpress.png" alt="worpdress logo">
            <img class="w-40 h-10 flex-shrink-0" src="/assets/images/2/joomla.png" alt="joomla logo">
            <div class="bg-white h-16 px-2">
                <img class="relative bottom-12 w-60 h-40 flex-shrink-0" 
                    src="/assets/images/2/magento.svg" alt="magento logo"
                >
            </div>
        </section>
        <section class="section__framework flex flex-row space-x-6">
            <img class="w-20 h-20 flex-shrink-0" src="/assets/images/2/laravel.jpeg" alt="laravel logo">
            <img class="w-36 h-20 flex-shrink-0" src="/assets/images/2/zend-framework.png" alt="zend framework logo">
            <img class="w-20 h-20 flex-shrink-0" src="/assets/images/2/symfony.png" alt="symfony logo">
            <img class="w-20 h-20 flex-shrink-0" src="/assets/images/2/codeIgniter.png" alt="code igniter logo">
        </section>
    </div>
</div>

<!-- v4 a une excellente syntaxe. outils: cms et framework se construisent autour -->

---

## L'évolution de PHP : son expension sur le marché des sites web

<div class="page__evolution--expension-sites pt-12 flex flex-col space-x-30">
    <table>
        <tr>
            <th>Année</th>
            <th>Parts de marché des sites utilisant PHP en millions</th>
        </tr>
        <tr v-click="1">
            <th>2002</th>
            <th>8</th>
        </tr>
        <tr v-click="2">
            <th>2007</th>
            <th>20</th>
        </tr>
        <tr v-click="3">
            <th>2013</th>
            <th>244</th>
        </tr>
    </table>
</div>

---

## L'évolution de PHP : son expension sur le marché de la programmation serveur

<div class="page__evolution--expension-seveur pt-12 flex flex-col space-x-30">
    <table>
        <tr>
            <th>Année</th>
            <th>Parts de marché des programmes sur serveurs utilisant PHP en pourcents </th>
        </tr>
        <tr v-click="1">
            <th>2010</th>
            <th>75%</th>
        </tr>
        <tr v-click="2">
            <th>2013</th>
            <th>75%</th>
        </tr>
        <tr v-click="3">
            <th>2016</th>
            <th>82%</th>
        </tr>
    </table>
    <a class="mt-16 text-yellow-400" href="https://w3techs.com/">sources: https://w3techs.com/</a>
</div>

---

## PHP en 2021 : Le déclin ?

<div class="page__2021--decay pt-12 flex flex-col">
    <ol class="w-full block flex flex-col space-y-6 text-left" v-click="1">
        <li class="text-xl">
            <h3>Parts de marché des programmes sur serveurs utilisant PHP : 
                <span class="text-red-400 font-extrabold text-lg">79%</span>
            </h3>
        </li>
    </ol>
    <div class="w-full text-left pt-24" v-click="2">
        <h2 class="text-yellow-400 text-5xl">
            Vaut-il la peine d'apprendre PHP en 2021 ?
        </h2>
    </div>
    <div class="w-full block flex flex-col mt-16 ml-100 space-y-0 text-left text-4xl" v-click="3">
        <h3>PHP se fait rattraper par Node.js</h3>
        <h3>Dans 5 ans plus personne n'utilisera PHP</h3>
    </div>
</div>

---

##

<div class="page__2021--fake-end ">
    <div class="absolute mt-50 ml-80">
        <p class="text-8xl">END</p>
    </div>
    <div class="absolute w-100 h-300 mt-45 ml-70 bg-black" v-click="1">
        <p class="text-8xl text-red-600">FAUX !</p>
    </div>
</div>

---

## PHP en 2021 : Pas de déclin !

<div class="page__today--better-shape pt-12 flex flex-col">
    <ol class="w-full block flex flex-col space-y-6 text-left">
        <li class="text-xl">
            <h3 class="text-green-400 font-extrabold text-lg">42% des sites web utilisent Wordpress</h3>
        </li>
    </ol>
    <div class="w-full flex flex-row space-x-16 text-left pt-24" >
        <h2 class="text-yellow-400 text-5xl" v-click="1">
            Vaut-il la peine d'apprendre PHP en 2021 ?
        </h2>
        <h2 class="text-yellow-400 text-5xl" v-click="2">
            OUI !
        </h2>
    </div>
    <div v-after="2">
        <div class="flex flex-wrap w-full mt-16 space-x-16">
            <img src="/assets/images/3/etsy.png" alt="logo de Etsy" class="flex-none w-20 h-20">
            <img src="/assets/images/3/facebook.png" alt="logo de facebook" class="flex-none w-30 h-20">
            <img src="/assets/images/3/slack.png" alt="logo de Slack" class="flex-none w-28 h-20">
            <img src="/assets/images/3/mailchimp.png" alt="logo de Mailchimp" class="flex-none w-28 h-20">
            <img src="/assets/images/3/tumblr.png" alt="logo de tumblr" class="flex-none h-20 w-20 bg-white">
        </div>
        <img src="/assets/images/3/rasmus-lerdorf-face.jpeg" alt="Rasmus Lerforf" class="absolute w-30 h-20 bottom-16 left-0 rounded-full" v-click="3">
    </div>
</div>

---

## PHP en 2021 : Ses faiblesses ?

<div class="page__2021--weaknesses pt-12 flex flex-row w-180">
    <div class="flex flex-col">
        <h3 class="mb-4">Une mauvaise réputation actuellement infondée. Beaucoup pensent que...</h3>
        <ol class="w-full block flex flex-col space-y-2 text-left">
            <li class="text-xl"><h3>PHP stagne depuis 20 ans.</h3></li>
            <li class="text-xl" v-click="1">
                <h3>PHP est resté une larve en v4, sans POO, instable, aux performances misérables.</h3>
            </li>
        </ol>
    </div>
    <div>
        <Tweet id="1161431862931349504" v-after="1"></Tweet>
    </div>
</div>

---

## PHP en 2021 : La réalité

<div class="page__2021--actually pt-12 flex flex-row w-full">
    <div class="flex flex-col w-200">
        <h3 class="mb-4">PHP en meilleure forme que jamais</h3>
        <ol class="w-full block flex flex-col space-y-2 text-left">
            <li class="text-xl" v-click="1"><h3>Fin 2020, la v8 est publiée</h3></li>
            <li class="text-xl" v-click="2"><h3>Facile à apprendre</h3></li>
            <li class="text-xl" v-click="3"><h3>Multiplateformes</h3></li>
            <li class="text-xl" v-click="4"><h3>Open source et gratuit (économie d'argent) </h3></li>
            <li class="text-xl" v-click="5"><h3>efficace et modulable (économie de temps)</h3></li>
        </ol>
    </div>
    <div class="flex flex-col space-y-4">
        <img src="/assets/images/3/logo_php8.svg" alt="php 8 logo" class="relative flex-none right-0 w-20 h-20 bg-violet-300 p-4">
        <img src="/assets/images/3/php_speed.png" alt="vitesse php" class="flex-none w-100" v-after="5">
    </div>
</div>

<!-- PHP7 est plus rapide que Python et Ruby -->

---

## PHP et vous : Le meilleur langage de programmation ?

<div class="page__you--best pt-12 flex flex-col w-full">
    <h3 class="mb-4">Dépend de votre objectif</h3>
    <div class="flex flex-row space-x-2 w-full">
        <img src="/assets/images/4/hunter_drone.jpeg" alt="drone tueur de pigeon" class="flex-none w-60" v-click="1">
        <p class="w-50" v-click="2">Logiciels systèmes embarqués en Java, Python, C, C++, C#</p>
        <img src="/assets/images/4/vaillant-pigeon.jpeg" 
            alt="vaillant pigeon de combat" class="flex-none w-60" v-click="3"
        >
    </div>
</div>

---

## PHP et vous : Un langage pour le développement web

<div class="page__2021--web pt-12 flex flex-col w-full">
    <h3 class="mb-4">PHP mérite votre attention si vous voulez devenir</h3>
    <ol class="w-full block flex flex-col space-y-2 text-left">
        <li class="text-xl" v-click="1"><h3>Developpeur web</h3></li>
        <li class="text-xl" v-click="2"><h3>Developpeur backend</h3></li>
        <li class="text-xl" v-click="3"><h3>Développeur web freelance</h3></li>
    </ol>
    <h4 v-click="4" class="mt-16">Salaire moyen annuel brut en France : 37 732 €</h4>
</div>

---

## PHP et vous : Ressources pour son apprentissage

<div class="page__2021--web pt-12 flex flex-col w-full">
    <ol class="w-full block flex flex-col space-y-2 text-left">
        <li class="text-xl" v-click="1">
            <h3>Apprendre le PHP avec GrafikArt https://grafikart.fr/formations/php</h3>
        </li>
        <li class="text-xl" v-click="2">
            <h3>Comprendre les principes SOLID en PHP par Lior Chamla https://learn.web-develop.me/a/lu6zp</h3>
        </li>
        <li class="text-xl" v-click="3">
            <h3>Se tenir à jour sur PHP avec l'AFUP https://www.youtube.com/user/afupPHP/featured</h3>
        </li>
        <li class="text-xl" v-click="4">
            <h3>Aller plus loin en sur le developpement informatique en français https://www.ledevweb.fr</h3>
        </li>
    </ol>
</div>

<!-- AFUP: Association Française des Utilisateurs de PHP -->

---

## Conclusion sur PHP

<div class="page__2021--web pt-12 flex flex-col w-full">
    <ol class="w-full block flex flex-col space-y-2 text-left">
        <li class="text-xl" v-click="1">
            <h3>
                même s’il a plus de 20 ans, s’améliore au fil des années.
                mauvaise réputation infondée.
            </h3>
        </li>
        <li class="text-xl" v-click="2">
            <h3>Créé pour le web, et représente 80% du des sites et services web en fonctionnement</h3>
        </li>
        <li class="text-xl" v-click="3">
            <h3>Un développeur PHP a des opportunités d'emploi assuré !</h3>
        </li>
    </ol>
    <h4 v-click="4" class="mt-16">Ce que permet PHP vous intéresse ? Qu'attendez-vous pour l'utiliser ?</h4>
</div>
