# ds-java_low_level

## Table of Content
* [Environment Java](#environment)
* [File Descriptions](#file-descriptions)
* [Écrire et exécuter votre premier programme Java](#examples-of-use)
* **Variables et types de données**
* **Opérateurs**
* **Instructions de contrôle**
* **Fonctions et méthodes**
  
# Feuille de route pour débuter en Java

Ce guide vous fournira une feuille de route étape par étape pour commencer à apprendre le langage de programmation Java, depuis l'installation des outils de développement jusqu'à la compréhension des concepts orientés objet.

## Environment Java

1. **JDK (Java Development Kit)** : Téléchargez et installez la dernière version du JDK depuis [le site officiel d'Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

2. **IDE (Environnement de développement intégré)** : Choisissez un IDE Java tel qu'Eclipse, IntelliJ IDEA ou NetBeans, et installez-le sur votre système.

3. **Configuration de l'environnement de développement**

  - 3.1 **Configurer le JDK dans votre IDE** : Suivez les instructions de votre IDE pour configurer le chemin d'accès au JDK que vous avez installé.

  - 3.2 **Créer un projet Java** : Créez un nouveau projet Java dans votre IDE.

## Écrire et exécuter votre premier programme Java

Utilisez le programme "Hello, World!" ci-dessous pour démarrer :

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
