# BSc-Thesis-Neurofeedback-Data-Analysis
This repository contains the files used to conduct statistical analysis for the BSc thesis project on Feedback Modality in a Gamified Neurofeedback Training Environment. The project incorporated auditory feedback into a Gamified Neurofeedback Environment to faciliate multi-modal feedback (auditory and visual). The source code of the Unity game (initially developed by Henriette Kohnen: @khnhenriette), with implemented auditory feedback, background music and live EEG data collection is included in this repository. 

Gameplay footage, as well as audio source files and images of the game scenes can be accessed in the following Google Drive: https://drive.google.com/drive/folders/1c8Ly29xh6OBagUoHv5z83eVd0AZ3EQDF?usp=drive_link. In the Gameplay folder, the videos ending on 'gameplay' show real footage from pilot testing. The video ending in 'sim' shows a simulation of the Neurofeedback training game, when the EEG headset is not connected. Therefore, a cursor is used to make in-game selections. During data collection, selections were made mentally by the participants. 

## MTgamified-AuditoryFeedback
Source code of the Neurofeedback Game. In order to effectively run the game and collect performance and EEG data, a g.tec [Unicorn Hybrid Black](https://www.gtec.at/product/unicorn-hybrid-black/) EEG headset is required. The built-in BCI classifier for Visually-Evoked Potentials is utilised in the Unity Neurofeedback game in order to allow mental in-game selections. 

## EEG Logs 
Raw EEG data collected during the neurofeedback training sessions for both conditions: Visual (V, unimodal) and Audio-Visual (AV, multimodal)

## BCI Performance Data
Labelled BCI logs from the neurofeedback game for each of the game scenes (Autumn, Winter, Summer). Can be analysed to determine accuracy and perform analysis.

## BCI Performance Analysis 
Analysis of the BCI performance data using python.

## GEQ Analysis 
Analysis of the [Game Experience Questionnaire](https://research.tue.nl/en/publications/the-game-experience-questionnaire) responses. Analysed using python. 
