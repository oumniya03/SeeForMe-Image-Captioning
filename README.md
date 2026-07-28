
# 👁️ See For Me - Application Mobile d'Image Captioning pour Malvoyants

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)](https://www.tensorflow.org/)
[![Android Studio](https://img.shields.io/badge/Android-Studio-green.svg)]()
[![Deep Learning](https://img.shields.io/badge/AI-Deep_Learning-red.svg)]()

<p align="center">
  <img alt="Logo See For Me" src="https://github.com/user-attachments/assets/54359dde-f93e-4930-a2d2-4bde5b8140a9" width="300" />
  
</p>

## 📝 Description du Projet (PFE)
Ce projet constitue mon **Projet de Fin d'Études (Licence)**. Il vise à développer une application mobile Android destinée à aider les personnes aveugles ou malvoyantes à mieux appréhender leur environnement.

Grâce à l'intelligence artificielle (Deep Learning), l'application analyse une photo prise par l'utilisateur, génère une description textuelle de la scène (**Image Captioning**) et la convertit en voix (Text-to-Speech). L'utilisateur entend ainsi une description de ce qui se trouve devant lui.

## 🎯 Objectifs
- Améliorer l'autonomie et la qualité de vie des personnes malvoyantes.
- Combiner la **Vision par Ordinateur** (CNN) et le **Traitement du Langage Naturel** (RNN/LSTM).
- Déployer un modèle d'IA complexe dans une application mobile.

## 🛠️ Architecture Technique

Le projet repose sur une architecture "Encoder-Decoder" :
1.  **L'Encodeur (CNN - VGG-16) :** Un modèle pré-entraîné (VGG-16) est utilisé via la technique de *Transfer Learning* pour extraire les caractéristiques visuelles clés de l'image.
2.  **Le Décodeur (RNN - LSTM) :** Un réseau de neurones récurrent (LSTM) génère une phrase descriptive mot par mot, en se basant sur les caractéristiques visuelles fournies par l'encodeur.

### 💻 Stack Technologique
- **Modélisation IA :** Python, TensorFlow, Keras, NumPy, Pandas.
- **Modèle de Vision :** VGG-16 (Comparé avec DenseNet-201 lors de l'étude).
- **Modèle de Langage :** LSTM.
- **Dataset :** Flickr8k (8 000 images et 40 000 légendes).
- **Application Mobile :** Android Studio, Java/Kotlin, TensorFlow Lite (pour le déploiement sur mobile), Text-to-Speech (TTS).

## 📊 Résultats & Performances

Lors de nos expérimentations, le modèle **VGG-16 a surpassé le DenseNet-201** pour notre cas d'usage :
- **Accuracy (Précision) :** 70.17%
- **Loss (Erreur) :** 0.8558
- Évaluation via le **BLEU Score** pour mesurer la qualité des légendes générées.

## 📸 Démonstration

Voici la vidéo de démonstration complète:


> https://github.com/user-attachments/assets/4ebdd0f3-b18a-4cb0-bac2-c0c582fdfb1d

## 📂 Contenu du Dépôt
- `Rapport finale.pdf et préesentation.pptx` : Contient le rapport final détaillé et la présentation PowerPoint du PFE.
- `video_demo.mp4` : La vidéo de démonstration de l'application en action.

## 👥 Équipe du Projet
- **Oumniya Moutaouakil**
- **El Bouti Houssine**
- *Encadrants : Pr. RIFFI Jamal & Pr. FILALI Hajar*
- *Université Sidi Mohamed Ben Abdellah - FSDM Fès*
