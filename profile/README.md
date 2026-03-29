# Team 9 
## Outline
TaskForge is a behavior-focused productivity platform that increases task completion by making progress rewarding. It helps users organize and complete daily responsibilities by reinforcing consistency through enemy combat, achievements, and character progression. The app is aimed at individuals who struggle with motivation in traditional productivity tools and respond better to external objectives, rewards and feedback loops. 

## Team members and their roles
Vincent Preseault : 300170802
- Backend developer
- DB admin
- DevOps

Nicolas Maalouly : 300272916
- Audio/Visual Design 
- UI/frontend developer
- Documentation (Meeting notes)

Shared Roles: 
- Project Management
- QA Testing
- Architecture

## Objectives (benefit to customer, key things to accomplish, criteria for success)
- Make accomplishing tasks engaging by rewarding real world task completions with various game elements
- Provide a easy to use task manager application that fits in customers daily routines
- Users must be able to efficiently create and manage tasks
- Must maintain a balance of productivity and gameplay so that game mechanics encourage productivity without distracting users

## Expected/anticipated architecture
- Mobile app programmed using Flame add-on to Flutter for both Android and iOS
- Monolithic backend REST Api programmed in go
- Postgres DB for application entity storage
- Backend deployed on Railway cloud hosting
- Authentication managed by Firebase Auth
- Logging and analytics managed in PostHog

## Anticipated risks (engineering challenges, etc.)
- Release on app stores
- Api versioning/service updates
- Finding the right balance between features on the backend vs frontend
- Learning new language (flutter/dart)
- Learning docker and CI/CD
- Learning audio and visual design to make the app feel polished
- Finding a client and finding users given that its a type 2 project
- Learning visual design
- Learning how to create audio and incorporating it

## Milestones 
- [x] Milestone 0 - Project start
- [x] Milestone 1 - "Task80"
  - Get 80% of the task page completed and delivered to users to get the app in their hands as fast as possible
  - Includes tasks with basic field, task labels and recurring task scheduling
- [x] Milestone 2 - "Battle80"
  - Get 80% of the battle page completed to give users exposure to the game elements
  - Inlcudes one monster, one character, basic combat system that provides one attack per task completion
  - Balanced equations for attack damage, monster health, player XP gain, player level thresholds
- [ ] Milestone 3 (Summer)
  - Expand art assets to ~30 characters and 4 characters, each with idle and attack animations
  - Reduce tech debt incurred during the winter term, expand test suite, establish CI/CD pipeline... 
- [ ] Milestone 4 (Fall)
  - Expand game elements like the combat system and character personalization
  - Expand productivity features based on client feedback/requests

## Legal and social issues.
- We anticipate no legal or social issues since the app is our original idea and all design elements will be created by us
  
## Initial plans for first release, tool setup, etc
- Features needed for Minimal Viable Product (MVP) 
  - Task list (one-time and recuring)
  - Basic set of monsters (minimum one for every day of the week)
  - Basic UI for mobile app to interact well with both of the above points
