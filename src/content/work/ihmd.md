---
title: I.H.M.D
publishDate: 2022-10-24 00:00:00
img: /assets/IHMD.png
img_alt: The Internet Horror Movies Databases
description: |
  Design, UX/UI, concept, gestion de projet, développement d'un site web responsive fullstack + API Rest => Horror Movies Database.
tags:
  - Design UX/UI
  - Backend
  - Frontend
  - API
  - Gestion de projet
  - User Testing
---

Ce projet est issu de la soutenance de projet de mon Bachelor concepteur développeur d'applications.
Il est basé sur un projet connu sous le nom de IMDb (internet movie database). Le but était de réaliser un projet axé sur les films et séries d'horreur => application web de base de données publique sur les films d'horreur listés avec toutes les sous-catégories qui pourraient en découler.
Un cahier des charges complet a été établi, une étude de marché a également été établie en se basant sur l'existant et ce qu'il était possible de mettre en place. Les choix des outils et technos on été faits.

La conception des wireframes "mobile first" a été inclu. Une maquette frontend statique pour établir un premier visuel du produit. Une charge graphique à été composée et choisie. La conception de la base données fut réaliser avec un MCD, MLD, shéma de base de données + dictionnaire de données.

Un outil existant proposant une API Rest public et open source a été utilisée (avec demande d'autorisations) pour peupler la BDD.
Un code métier a donc été mis en place, fonctionnant avec des commandes au terminal. Se code permet lors d'une  installation de projet, de créer puis lancer la construction et le remplissage de données issus de l'API public.

Coté frontend ce projet est resté sur la base de twig + Bootstrap avec quelques composants javascript via Webpack-encore bundle connu sous le nom de Symfony-UX (Vuejs).
Un système de gestion des utilisateurs connecté a été initié dans ce MVP 1.0 et il était prévu à terme dans une 2.0 de gérer un système de profil utilisateur, la gestion des favoris et l'ajout de commentaires sur une page de film.

Une plateforme de backoffice à été mise en place (EasyAdmin bundle) et intégré avec le visuel de l'ensemble du projet. Accessible uniquement depuis le menu et "SI" connecté avec un compte  ayant des droits administrateur ou super admin. Il est alors possible de gérer la liste des films, modifier les fiches (changement de catégorie, sous-catégorie d'un film), superviser/modérer les profils des nouveaux inscris mais également et surtout les commentaires publiés soumis à validation. Et ce afin de respecter la charte de "bonne conduite" présente sur ce projet web.

Le projet a été mis en ligne mais par maque de crédit sur le serveur web, il n'est actuellement plus en ligne.