
# Rootdetection.aar

Module Android encapsulé dans un .aar pour la détection de root.

## Présentation

Ce module compile en une bibliothèque AAR réutilisable fournissant une API pour :

- Détecter si un appareil Android est rooté  
- etc.

Le code source n'est pas inclus, seul le bytecode compilé.

## Installation

Récupérer le .aar depuis la [release GitHub](https://github.com/Talentn/RootDetector/releases/tag/rootdetection-v1.0).

Ou dans Gradle :



```groovy 
dependencies {
  implementation 'com.github.talentn:rootdetection:1.0.0'
}
```

## Utilisation

Importer la classe :

```kotlin
import com.package.RootChecker
```

Instancier :

```kotlin
val detector = RootChecker()
```

Appeler les méthodes :

```kotlin
if (detector.isRooted()) {
  // Appareil rooté
}
```

## Méthodes

- **isRooted()** : détection du root


## Contribution

Les contributions sont les bienvenues ! 



N'hésitez pas à me préciser si vous souhaitez ajouter ou modifier des informations dans cette documentation pour votre bibliothèque AAR.
