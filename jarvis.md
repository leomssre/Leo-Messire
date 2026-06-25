# 🤖 Projet Jarvis - Assistant Autonome Multi-Agent

## 📝 Présentation Générale
Jarvis est un assistant virtuel autonome et intelligent développé en **Python**. Initialement conçu comme un script local avec interface graphique (Tkinter), le projet a évolué vers une **architecture modulaire moderne** propulsée par un serveur web **Flask**. 

L'objectif principal de Jarvis est d'offrir une interface centralisée, fluide et ultra-réactive capable d'interagir avec l'utilisateur par la voix ou le texte, de gérer une mémoire contextuelle et d'exécuter des tâches d'automatisation système.

---

## 🛠️ Fonctionnalités Clés

*   **🧠 Architecture Multi-Agent & Multi-Modèles :** Intégration et orchestration de plusieurs grands modèles de langage (LLM). Le cœur du système repose sur **Gemini 2.5 Flash** pour sa rapidité et sa gestion des contextes, avec la possibilité de basculer dynamiquement sur d'autres modèles (Grok, GPT, Claude, Mistral) selon les besoins de la tâche.
*   **🌐 Backend Web Flask :** Transition d'une interface de bureau classique vers une architecture client-serveur robuste avec un backend Flask, permettant une meilleure séparation des fonctionnalités et une base solide pour de futures extensions (interface web responsive).
*   **🎙️ Interaction Vocale :** Module de reconnaissance vocale (Speech-to-Text) et synthèse vocale (Text-to-Speech) pour une utilisation mains libres totalement fluide.
*   **💾 Gestion de la Mémoire :** Implémentation d'un système de mémoire à court et long terme permettant à l'assistant de se souvenir des interactions passées et de maintenir un contexte cohérent.
*   **👁️ Analyse Visuelle :** Capacité d'analyser des images ou des captures d'écran en exploitant les capacités multimodales des API utilisées.
*   **⚙️ Automatisation Système :** Scripts intégrés permettant à Jarvis d'interagir directement avec le système d'exploitation pour lancer des applications ou exécuter des commandes.

---

## 💻 Stack Technique

*   **Langage :** Python 3
*   **Framework Web / Backend :** Flask
*   **Modèles d'IA / API :** Google Gemini API (Gemini 2.5 Flash), OpenAI API, Anthropic, Mistral AI, xAI
*   **Audio :** Bibliothèques de Speech-to-Text et Text-to-Speech Python
*   **Gestion de version :** Git & GitHub

---

## 🚀 Ce que ce projet m'a apporté

Le développement de Jarvis m'a permis de pousser mes compétences en programmation bien au-delà des scripts classiques :
1.  **Conception logicielle :** Comprendre l'importance de refactoriser son code (passer de Tkinter à Flask pour assainir l'architecture).
2.  **Gestion des API & de l'asynchronisme :** Manipuler plusieurs clés d'API, gérer les quotas, les temps de réponse et formater correctement les requêtes multimodales.
3.  **Autonomie :** Résoudre des problématiques complexes de configuration d'environnement et de conflits de bibliothèques.
