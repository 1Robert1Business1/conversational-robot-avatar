# Conversational Robot Avatar

A real-time personalised robot avatar combining large language models, 
3D facial modelling, and speech synchronisation for natural human-robot interaction.

## Overview

The system creates a responsive avatar by integrating ChatGPT for dialogue 
generation with Furhat Robotics for physical expression and speech output. 
Photogrammetry was used to build realistic 3D facial models, with blendshapes 
applied in Blender to enable dynamic expression control.

## How it works

1. A participant's face is captured using photogrammetry and reconstructed in Blender
2. Blendshapes are applied to enable real-time facial expression control
3. The Furhat SDK maps the 3D model onto the robot and handles speech synthesis
4. ChatGPT API generates context-aware responses during live conversation
5. Python manages the backend — API calls, conversation flow, and Furhat remote control

## Results

- Achieved natural speech and facial expression synchronisation in real time
- Successfully deployed personalised avatars for two participants
- Awarded a Distinction — MSc Artificial Intelligence, University of Kent (2024)

## Tech Stack

Python · ChatGPT API · Furhat SDK · Blender · Photogrammetry

## Structure

- `notebooks/` — Jupyter notebooks for ChatGPT integration, voice interaction, and gesture control
- `assets/blender/` — 3D facial models and blendshape exports
- `assets/furhat/` — Face application configs and Blockly conversation flows
- `docs/report.pdf` — Full dissertation and methodology

## Note

Some participant images and Unity assets are excluded for privacy and licensing reasons. 
Full methodology, results, and visual outputs are documented in `docs/report.pdf`.
