# Speech Command Recognition Subsystem for Autonomous Warehouse Robots

This repository contains the source code for the bachelor's diploma project.

## Overview
The project focuses on developing an intelligent voice command recognition subsystem for autonomous warehouse robots, operating on the principles of Edge Computing. 

**Key components:**
1. **Fine-Tuning Module:** Adapting the OpenAI Whisper Small model to the Ukrainian language using the Google FLEURS dataset.
2. **Fail-Safe Controller:** A logical controller (`robot_brain`) that filters transcriptions using fuzzy search and a strict priority hierarchy to prevent hardware accidents.

## Requirements
All necessary libraries to run the notebook are listed in `requirements.txt`.

## Developer
Viktoriia Hlushkova
