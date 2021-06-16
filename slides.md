---
theme: apple-basic 
class: 'text-center' 
highlighter: shiki 
info: |
## Introduction à PHP
---

# Introduction à PHP

<div class="pt-12 flex flex-row space-x-70">
    <ol class="w-60 relative block flex flex-col space-y-8 text-left">
        <li class="text-xl"><h2>1. Origines</h2></li>
        <li class="text-xl"><h2>2. Évolution</h2></li>
        <li class="text-xl"><h2>3. Aujourd'hui</h2></li>
        <li class="text-xl"><h2>4. Vous et PHP</h2></li>
    </ol>
    <img class="" src="/assets/images/1/php_pachyderme.png" alt="php-pachyderme">
</div>
<a class="relative inset-y-30 inset-x-84" href="https://www.linkedin.com/in/snitpro/">Par Sébastien NOBOUR</a>

---

## Les origines de PHP: la v1, PHP/FI 

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
<a class="relative inset-y-40 inset-x-180 text-xs text-blue-gray-300" href="https://www.linkedin.com/in/snitpro/">Sébastien NOBOUR</a>

<!--
né 22 novembre 1968 au Groenland, 
nationalité danois canadien
Ingénieur système

produire des pages web dynamiques plus rapidement qu’avec d’autres langages comme Perl-CGI ( remplir page web de données reçues d’un serveur web distant) 
-->

---

## L'évolution de PHP: la v2 et v3

<div class="page__evolution--v2 pt-12 flex flex-row space-x-70">
    <ol class="w-60 relative block flex flex-col space-y-6 text-left">
        <li class="text-xl"><h3>PHP/VI v2 sortie en 1996, mais impopulaire</h3></li>
        <li class="text-xl" v-click="1">
            <h3>En 1997, PHP v3 (Hypertext Preprocessor) est publié.</h3> 
        </li>
        <li class="text-xl" v-click="2">
            <h3 class="text-yellow-400">
                Résultat du redéveloppent du cœur de PHP/FI v2 par Andi Gutmans et Zeev Suraski, avec Rasmus Lerdorf.
            </h3>
        </li>
        <li class="text-xl relative bottom-35 bg-black h-40" v-click="3">
            <h3 class="text-green-400">
                Interface pour de multiples bases de données, protocoles et API, la facilité d'extension du langage, OOP
            </h3>
        </li>
    </ol>
    <div class="flex flex-col space-y-4">
        <section class="section__andy">
            <img class="w-20 h-20" src="/assets/images/2/andi-gutmans.jpeg" alt="Andi Gutmans">
            <a href="https://twitter.com/andigutmans" target="_blank" 
                class="text-xl text-light-blue-500"
            >
                <carbon-logo-twitter />@andigutmans
            </a>
        </section>
        <section class="section__zeev">
            <img class="w-20 h-20" src="/assets/images/2/zeev-suraski.jpeg" alt="Zeev Suraski">
            <a href="https://twitter.com/zeev" target="_blank" alt="twitter de Zeev Suraski" 
                class="text-xl text-light-blue-500"
            >
                <carbon-logo-twitter />@rasmus
            </a>
        </section>
    </div>
</div>
<a class="relative inset-y-40 inset-x-180 text-xs text-blue-gray-300" href="https://www.linkedin.com/in/snitpro/">Sébastien NOBOUR</a>

<!--
né 22 novembre 1968 au Groenland, 
nationalité danois canadien
Ingénieur système

produire des pages web dynamiques plus rapidement qu’avec d’autres langages comme Perl-CGI ( remplir page web de données reçues d’un serveur web distant) 
-->
