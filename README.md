# GDIM32 In Class Activities
## W1
### Activity 1
Our group came up with several tips:
1. First build is longest, more building, easier to build, build as early as possible.
2. Turn in something on time rather than nothing, you can work on it after and turn it in a day late and still receive an A.
3. Work on it if only for a couple minutes. Something is better than nothing. 
4. Go to office hours once every week or every other week.
5. Ask on discord “Questions” channel, questions you have may already be answered.
6. Playtest your own game more. Don’t be afraid to ask people to playtest your game.

### Activity 2
1. Value of x is 10
2. Value of x is 2
3. In the PrivateMessage () method, “hello world” is put in the console every frame because of the update method
4. Monobehaviour
5. At the start of the game, assigns 10 to x and therefore shows “x = 10” in the console
6. 10 is argument, int x is parameter 
7. There is no object in front of translate. Translate only works on object. Translate is being called on a class name
8. Use _playerTransform variable

### Activity 3
[MG1 breakdown Google doc](https://docs.google.com/document/d/1ItG4dZjoaa4lzg4txGNIlp00ONVVm-BPawFd5McfTTc/edit?usp=sharing)

## W2
### Activity 1
![20260113_193832](https://github.com/user-attachments/assets/95b54b45-2923-4ded-be69-7397d442d1c2)

### Activity 2
[MG2 Repository Link](https://github.com/UCI-GDIM32-W25/mg2-lpher/commit/dc6def181d67887701e29f6e3420baf6a5f651a9)

I worked on setting up the game objects first, follwed by creating a script for the penguin as I wanted to work on player movement before anything else. For the game objects I set up their respective components like colliders for the floor, player, and coin. To create the core mechanic of the penguin jumping, I created an if statement for when ever the player presses down on the SPACE key.

## W3
### Activity 1-2
My partner is Milla.

### Activity 3
![20260120_191621](https://github.com/user-attachments/assets/9d7d492a-5ec3-4b73-840f-ee275180f09f)

## W4
### Activity 0
My partner is Milla.

### Activity 1
The Locator objects all get deleted except for the most recent one when the game is ran. This happens because of the if statement in the awake method where it destroys all Locator game objects except one.

### Activity 2
![20260127_192748](https://github.com/user-attachments/assets/98ce4fed-1a3c-468d-a282-9784230cf91c)

### Activity 3
[MG4 Repository Link](https://github.com/lpher/mg4-lpher/commit/ced861293211d319043b9fa6b5b689f7e4bb75ff)

I worked on setting up the basis of the game with a ground game object and a player gameobject with colliders and a rigidbody for the player to make to fall. I also created a player script so that the player game object can jump.

## W5
### Activity 1
I don’t feel fully comfortable or confident with interfaces and abstract classes yet, so I think as concepts they are complicated and confusing. I had to keep glancing back at the week 5 pre-learning slides to fix the code. Because of this I would keep this design rather than changing it because if it works then it works. This feels like the safest thing to do.

### Activity 2 (Be more specific here)
The Model is represented by the classes EnemyStats and ItemW5Demo2, which store game data such as the names, dialogue lines, and item information without containing any UI or input logic. The View is represented by the classes DialogueBubble and InventoryUI, which handle the displaying of information to the player such as the dialogue text and inventory contents. The Controllers are represented by the classes EnemyW5Demo2 and PlayerW5Demo2 as they contain the logic that reacts to player input and game state such as checking player distance or keyboard input, using that logic to decide when to update the Views using data from the Models.

### Activity 3
#### Scenario 1
Beats would be prefabs. Allows transform and sprite. Scriptable data describing where in the song has to be hit. 

#### Scenario 2
The stats and data about abilities would be the model. Gameplay code carrying our abilities would be the controller. The view is the UI for activating the ability and any visual results.

#### Scenario 3
States useful to plants or players. Players could have different mining or planting behavior having enums for each behavior/state. Enums and states can be used for the plant's growth state like a sapling to a tree. States are better for web or circle than linear progression.

### Activity 4
Attendance: Rebecca Feng, Frances Nareh Kim, and Landon Peev Xwm Her.

[Proposal Draft Doc Link](https://docs.google.com/document/d/12oXcMbRqu-4vIfI7XU0rpLQhKyyF9Gy7RNBljYCJIrA/edit?usp=sharing)

## W6
### Activity 1
[Demo Notes and Project Usefulness](https://docs.google.com/document/d/1QVWgpU_2Zar1QHjAMIz1v_bz12q1Gy1lPDye7t7_sV8/edit?usp=sharing)

### Activity 2
Attendance: Nansong Sun and Landon Her. Rebecca Feng and Frances Nareh Kim attended VGDC's Game Developer's Week.

[Proposal Final Draft Doc Link](https://docs.google.com/document/d/12oXcMbRqu-4vIfI7XU0rpLQhKyyF9Gy7RNBljYCJIrA/edit?usp=sharing)

## W7
### Activity 1
- State machine useful cause there are two mutually exclusive states that cannot occur at the same time and can switch between states
- Can also control animations, effects, and UI
- Not separating states makes things confusing
- Vector used to determine line of sight to player
- Raycast throwing a ray into scene and seeing if it hits something
- Can edit its distance with parameters
- Raycast returns true or false
- If it hits something is will go into brackets where it will check if what it hit was the player
- Spherecast looks at area within a sphere instead of a single point a raycast would give

### Activity 2
Attendance: Frances Nareh Kim, Rebecca Feng, Landon Her, Nansong Sun

### Actvity 3
![W7 Final Break down](https://github.com/user-attachments/assets/caa4669d-d8b6-4470-9f2a-d082668dd62c)

### Activity 4
[Nerd Cluster Tasks](https://docs.google.com/spreadsheets/d/1Zv6t-jtaA3FyTzVV6nuGgsbLFK90LGVoSos6l5H0YpU/edit?gid=0#gid=0)

### Activity 5
