# MultiParticleTracker

Overview

MultiParticleTracker is a Python-based system for tracking small particles in video sequences. It supports both manual selection of individual particles and automatic multi-particle tracking with velocity calculations. The project originated from experimental research on tracking bead movement on a sphere, improving upon traditional 2D tracking methods.

Features

Automatic particle detection using OpenCV contour-based processing

Manual selection mode for precise tracking of a single particle

Multi-particle tracking with unique ID assignment for each particle

Velocity calculation based on pixel-to-micrometer conversion

Sphere-aware tracking (for cases where particles move on a curved surface)

Custom thresholding & filtering for noise reduction

Background & Motivation

This project was developed to address challenges in tracking dense and overlapping small particles in experimental setups. Initially, a 2D tracking system (measure.py) was implemented, but it only provided a single velocity. Later, a manual tracking approach (trace_bead.py) was introduced, allowing researchers to select specific particles.

However, tracking dense particles and handling overlapping movement remains a challenge. This repository integrates automatic multi-particle tracking and explores potential deep learning enhancements for improved accuracy.
