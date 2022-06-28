# Unreal Engine Live Project
I worked on creating various game features using blueprint logic.

## Project Overview
This project was meant to be a learning experience for using the Unreal game engine. It involves working in an Agile/Scrum environment, and I was tasked to implement a variety of features for a game.

## Index

- [Pain Causing Volume](#pain-causing-volume)
- [Level Sequencer](#level-sequencer)
- [Key Blueprint](#key)
- [UI Elements](#key)
- [End Goal]()
- [UI Elements](#key)


## Pain Causing Volume

A pain causing volume is placed to respawn the character when entering a dead-zone/restricted area.

<img src="https://user-images.githubusercontent.com/98930139/176229609-47beeb0d-3f71-4875-b9ca-f81a694f101c.png" width="700" height="400">

## Level Sequencer

I utilized a level sequencer to animate moving platforms.

<img src="https://user-images.githubusercontent.com/98930139/176234695-091767c3-1f40-49fd-9b06-d782c7baae93.gif" width="700" height="400">

## Key

For this task, I had to perform blueprint logic to let the game mode know if the key has been picked up.

<img src="https://user-images.githubusercontent.com/98930139/176240654-c9d363a3-fd1c-4064-ba6b-bfaee7b72f6e.png" width="700" height="250">

## UI Elements

On this story, I had to display and update the various items that have been picked up.

<div float="left">
    <img src="https://user-images.githubusercontent.com/98930139/176253481-ed4cec1e-6724-4fa1-96e4-bd7e75f1c850.gif" width="400" height="250">
    <img src="https://user-images.githubusercontent.com/98930139/176253577-2e307eb6-b6b7-42cd-b12a-110e5b4269d5.gif" width="300" height="150">
</div>

<img src="https://user-images.githubusercontent.com/98930139/176254312-1f86eb57-db1b-4545-95d2-fb3219f839f3.png" width="700" height="250">

<img src="https://user-images.githubusercontent.com/98930139/176254962-2596b312-d686-40f7-be10-4ad236811337.png" width="700" height="250">

## End Goal

Here, I had to create blueprint logic to set game conditions and display a game completion HUD which includes a functional button that restarts the game.

<img src="https://user-images.githubusercontent.com/98930139/176320257-95e3aed9-3bb4-4b46-b913-60c71341d7f5.gif" width="700" height="400">

First, I had to create a function that checks if all collectibles have been picked up, then display the HUD if true.

<img src="https://user-images.githubusercontent.com/98930139/176321112-b4e48211-57f1-4ca4-8557-53abe08940dd.png" width="700" height="250">

Once I've created the function, I placed a trigger box at the desired end zone to call the function.

<img src="https://user-images.githubusercontent.com/98930139/176321919-822e8fc5-6b3a-48cf-a270-ff1a93afc3ad.png" width="700" height="250">