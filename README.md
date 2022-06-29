# Unreal Engine Live Project
I worked on creating various game features using blueprint logic.

## Project Overview
This project was meant to be a learning experience for using the Unreal game engine. It involves working in an Agile/Scrum environment, and I was tasked to implement a variety of features for a game.

## Index

- [Pain Causing Volume](#pain-causing-volume)
- [Level Sequencer](#level-sequencer)
- [Key Blueprint](#key)
- [UI Elements](#key)
- [End Goal](#end-goal)
- [Obstacles & Health System](#obstacles--health-system)


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

## Obstacles & Health System

For my final story, I had to create a health & damage system, and design an obstacle course.

I decided to create a blueprint interface to store my damage event, and call it when the character gets hit by a damage causable object.

<img src="https://user-images.githubusercontent.com/98930139/176323798-322707f9-1a07-4fe7-82c6-6d333e399428.png" width="700" height="250" title="Character takes damage">
<hr>

Before I designed the obstacle course, I created a few blueprint objects to act as obstacles.

**Rotating Hammer(Damage Causable)(Rotating Movement Component)**

<div float="left">
    <img src="https://user-images.githubusercontent.com/98930139/176325165-634369ce-5156-4ebc-aec0-49a96330a9d7.gif" width="400" height="250">
    <img src="https://user-images.githubusercontent.com/98930139/176325572-8d26bec6-5fa6-4d24-8630-ed856edfd2e4.png" width="400" height="250">
</div>
<hr>

**Tilting Plank(Physics Constraint Component)**

<div float="left">
    <img src="https://user-images.githubusercontent.com/98930139/176326750-d9426acd-8ef9-4c3f-ad77-34b83df9267e.gif" width="400" height="250">
    <img src="https://user-images.githubusercontent.com/98930139/176327001-77189c5f-b9e5-4ca7-a0a9-d46632ac6bd6.png" width="400" height="250">
</div>
<hr>

**False Floors**

I decided to create a blueprint consisting of two identical platforms surrounded by a box collision, upon overlap, a random platforms' collision response is set to overlap and visibility is disabled at random, resulting in the character falling through.

A delay was included in order to reset the collision response and visibility.

<div float="left">
    <img src="https://user-images.githubusercontent.com/98930139/176328254-293034d5-9af7-4830-a244-38d65be2390a.gif" width="400" height="250">
    <img src="https://user-images.githubusercontent.com/98930139/176328420-f7e4ed2f-0698-4ed5-a9f8-bbac8da414d0.png" width="400" height="250">
</div>