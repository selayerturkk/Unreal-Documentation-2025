# Overview

This repository compiles the Unreal Engine Documentation Guidelines alongside example documentation produced by multiple simulation teams: Data Platform, Experiments, and Visual Occlusion.
It serves as a reference for writing, organizing, and maintaining Blueprint-based technical documentation across Unreal Engine projects.

# Contents

## Documentation Guidelines 

Source: Guidelines.pdf

Defines standards for:
- Variable and function naming conventions
- Boolean prefixes and PascalCase formatting
- Node commenting and block-comment color schemes
- Blueprint flow organization (wire alignment, node limits)
- Documentation structure per feature (goal, variables, branches, logic, screenshots)

## Platform Documentation

Source: Platform.pdf

Documents systems used in Unreal’s simulation framework, including:
- Vehicle brake, engine, torque, and gear-shift logic
- Light and radio control systems
- Multiplayer replication examples for in-game systems
- Example flowcharts and logic branches for Blueprint functions

## Experiments Team Documentation

Source: Experiments.pdf

Focuses on the interactive and sensory layers of the simulation:
- Audio feedback (brake sounds, engine sounds, dirt-road effects)
- Mouse-based camera control and zoom functions
- Collision handling with dynamic feedback logic
- Initialization and steering wheel SDK setup

## Visual Occlusion Documentation

Source: Visual Occlusion.pdf

Describes the adaptive and non-adaptive visual occlusion systems:
- Toggle and timer logic for screen fading
- Adaptive duration logic for occlusion feedback
- Input mapping from steering wheel, keyboard, and controller
- Implementation of event-driven occlusion timers

## Data Team Documentation

Source: Data.pdf

Provides detailed documentation for simulation data capture:
- Laser-based lateral position detection
- Road-type feedback and steering vibration logic
- Curve percentage calculation and vehicle telemetry
- Integration of Logitech SDK for haptic feedback


# Purpose

The purpose of this repository is to:
- Provide a standardized approach to Unreal Engine documentation
- Promote clarity and consistency across different development teams
- Enable efficient onboarding of new contributors
- Showcase strong internal examples of well-documented technical work

# How to Use
- Review the Guidelines.pdf file for general standards.
- Explore the example files to see the guidelines applied in practice.
- Use the included templates to structure your own Unreal Engine documentation.
- Contribute improvements or extensions through pull requests.

# Acknowledgments

Special thanks to the Data, Platform, Experiments, and Visual Occlusion teams for contributing example documentation, and to all collaborators helping standardize Unreal documentation practices across projects.
