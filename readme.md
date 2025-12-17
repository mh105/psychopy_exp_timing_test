# Timing test task
Last edit: 12/17/2025

## Edit history
- 12/17/2025 by Alex He - added text screens before starting trials to set up light sensors
- 12/16/2025 by Alex He - created finalized first draft version

## Description
This is a toy experiment used to test the visual display timing precision of PsychoPy tasks. It needs to be used with a photcell (light sensor) device along with an external recording system with high sampling rate. ANT-Neuro EEG recording under 2kHz is used to receive triggers from PsychoPy as well as from the light sensor connected through the Cedrus StimTracker Quad device. Note, double trigger setting should be enabled on the M-pod using the Xidon 2 software.

## Outcome measures
- Timing difference between triggers sent from PsychoPy and from the light sensor detected luminance change.
