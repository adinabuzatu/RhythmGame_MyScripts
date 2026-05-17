# Symphony Sync

Developed a mobile AR rhythm-game prototype in Unity for [**SPOT**](https://www.spotgroningen.nl/), Groningen, that transformed live classical concerts into interactive gameplay experiences for audiences aged 16–24.

## Problem

- How can AR be applied to enhance the experience of live classical music?
- How can interactivity engage and help make a younger target audience appreciate this music?
- This project is about creating an extra experience to live classical music.

## My Solution

- A mobile AR experience that transformed classical concerts into an interactive, game-like environment. 
- By introducing real-time AR interaction, the experience reframed classical music as something participatory and immersive rather than passive. 
- Visitors can engage with AR notes and visual effects synchronized to the live orchestral music through gestures like tapping, holding and swiping. 
- The prototype aims to bridge the gap between traditional concert culture and the interactive digital experiences younger audiences are already familiar with.

# My Contribution

## Programming

**What I would refine:**

- I would move the hardcoded beat indexes into one clean data file.
- I would store note type, time, position and score in one list of note events.
- I would use *AudioSettings.dspTime* or *audioSource.timeSamples* instead of the *Stopwatch*, so that timing stays closer to the actual audio.
- I would add validation for missing files, duplicate IDs and unsorted timestamps.
- I would use object pooling for notes instead of creating and destroying objects every time.

## Research

The research combined qualitative user research and usability testing.

**Pre-development**

In the pre-development phase, I conducted: 
- focus groups,
- interviews,
- desk research,
- persona mapping.

<img width="550" height="680" alt="Image" src="https://github.com/user-attachments/assets/561734cf-5e3e-4344-a18a-67db9e547a65" />

The purpose of this research was to understand:
- how younger audiences perceive classical music,
- what types of games and interactions they enjoy,
- what would motivate them to attend concerts.

**Post-development**

- I designed user testing sessions to validate whether AR note interactions (tapping, holding and swiping) felt natural within a physical concert environment.
- I asked participants to complete gameplay tasks independently while I measured their reaction time, how they navigate the scene, how frequently they made mistakes and how easy was to understand the mechanics.
- I tracked if the player was able to navigate the menus on their own, without any help and observed facial expressions to see if they find it easy to navigate.

## Agile Workflow

I coordinated a team of five developers and designers while managing feature integration through GitHub. 
<br> Because multiple team members were simultaneously working on gameplay systems, UI and AR interactions in Unity, version control quickly became one of the project’s biggest **technical challenges**.

Because of it, I introduced some GitHub collaboration practices for the team:
- feature branches for individual tasks,
- more frequent commits,
- pull request reviews before merges,
- communication about which Unity scenes or prefabs were being edited.
To minimize Unity merge issues, I encouraged teammates to avoid editing the same scenes simultaneously and helped establish clearer ownership over project areas.

<img width="1532" height="718" alt="Image" src="https://github.com/user-attachments/assets/17c2b505-a564-4de2-813f-63bd3d526e67" />

**Scrum Master**
- I organized the production pipeline through backlog management, task prioritization and sprint planning.
- During sprint meetings, I reviewed progress individually with each team member, identified blockers, adjusted deadlines when necessary and ensured development stayed aligned with milestone goals.
- This role improved my leadership, communication and project management skills within an agile game development environment.

<img width="1103" height="686" alt="Image" src="https://github.com/user-attachments/assets/34490ece-ba24-41a2-bb99-a5b58cd7d3b9" />
