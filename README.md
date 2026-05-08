# Coccinelle-Ecosystem-Simulation-in-Python
# 🐞 Ladybug Ecosystem Simulation - NSI Practice Exam

This project is a Python-based biological simulation developed for the **Numérique et Sciences Informatiques (NSI)** specialty for the French Baccalaureate. It models the population dynamics of ladybugs and their prey in a closed ecosystem.

## Overview
The simulation uses **Object-Oriented Programming (OOP)** to represent individual ladybugs and their life cycles. It tracks population growth, hunting efficiency, and aging over several simulation days.

## Key Features
- **Hunting Mechanics**: Ladybugs hunt aphids based on food availability. Their nutrition level increases or decreases depending on their success.
- **Reproduction System**: Female ladybugs can produce descendants (one male, one female) if they reach a specific nutrition threshold.
- **Survival & Aging**: Each ladybug has a randomized lifespan (200-350 days). The system automatically handles mortality and daily aging.
- **Dynamic Ecosystem**: Prey population (aphids) follows a 20% natural daily growth rate, balanced by ladybug predation.

## Technical Concepts
- **OOP (Classes & Methods)**: Encapsulation of ladybug attributes (sex, age, nutrition).
- **Simulation Logic**: Implementation of an `evolution` function to manage daily ecosystem updates.
- **Randomization**: Use of the `random` library to simulate biological unpredictability (lifespan, food consumption).
- **List Management**: Dynamic tracking of populations and new births.
