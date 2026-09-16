# VICON Dataset

Hand-object manipulation dataset recorded with the VICON-glove (a visual-inertial glove with eight force-sensitive resistors) and a single RGB-D camera. Each session provides synchronized hand skeleton trajectories, refined 6-DoF object trajectories, object meshes, contact points on the object surface, and calibrated normal forces.

This repository accompanies the paper *VICON: Visual-Inertial-Contact based Hand-Object Tracking for Manipulation Datasets* (under review). The dataset and loading code will be released upon publication.

## Contents (planned)

| Item | Description |
|---|---|
| RGB-D frames | Color and depth images at about 30 Hz |
| Hand trajectories | Hand skeleton poses from the visual-inertial glove |
| Object trajectories | Refined 6-DoF object poses per frame |
| Object meshes | Meshes reconstructed from monocular video |
| Contact records | Per-frame contact points (object and camera frames), signed sensor-surface distance, and calibrated normal force for each active FSR |
| Ground truth | Motion-capture object poses for the evaluation sessions |

## Status

- [ ] Dataset release
- [ ] Data loader and visualization scripts
- [ ] Documentation of the file format

## License

To be announced with the release.
