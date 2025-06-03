lang: [en](README.md) | [de](README.de.md)

# Discord Virtual Room (idea)

**An experimental idea to make voices in Discord sound like they come from different directions**

This is an early concept for a tool that lets you place voices in a Discord voice channel in different positions.  The goal is to make it sound like you are sitting in a room with other people – using stereo, surround or other spatial audio effects.

## Project Goals

The tool should support two main features:

1. **Personal spatial audio**  
   Each user can decide where they hear other people in the virtual space (for example: left, right, front, back).

2. **Shared channel layout**  
   It should also be possible to set one common layout for the whole channel (for example by certain users, roles or bots), so that everyone hears the same positions.

## Concept Details

- Each voice is processed separately.
- Voices are placed in space using stereo panning or 3D sound filters.
- The goal is to create a more natural and realistic listening experience.
- This can be done with a Discord bot or with external audio tools (like audio routing software).
