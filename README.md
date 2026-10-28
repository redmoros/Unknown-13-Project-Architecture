# Project Architecture

```text
PROJECT_ROOT/
│
├── Assets/
│   ├── _Project/
│   │   ├── Art/
│   │   │   ├── Characters/
│   │   │   │   ├── Player/
│   │   │   │   └── NPCs/
│   │   │   ├── Environments/
│   │   │   │   ├── Architecture/
│   │   │   │   ├── Props/
│   │   │   │   ├── Vegetation/
│   │   │   │   └── Decals/
│   │   │   ├── Materials/
│   │   │   ├── Textures/
│   │   │   ├── Shaders/
│   │   │   ├── VFX/
│   │   │   └── Lighting/
│   │   │
│   │   ├── Audio/
│   │   │   ├── Music/
│   │   │   ├── Ambience/
│   │   │   ├── SFX/
│   │   │   │   ├── Foley/
│   │   │   │   ├── Interaction/
│   │   │   │   ├── Doors/
│   │   │   │   └── Horror/
│   │   │   ├── Dialogue/
│   │   │   ├── Voice/
│   │   │   └── Mixers/
│   │   │
│   │   ├── Game/
│   │   │   ├── Core/
│   │   │   │   ├── Bootstrap/
│   │   │   │   ├── Composition/
│   │   │   │   ├── Events/
│   │   │   │   ├── State/
│   │   │   │   ├── Time/
│   │   │   │   └── Utilities/
│   │   │   │
│   │   │   ├── Gameplay/
│   │   │   │   ├── Player/
│   │   │   │   ├── Interaction/
│   │   │   │   ├── Objectives/
│   │   │   │   ├── Dialogue/
│   │   │   │   ├── Narrative/
│   │   │   │   ├── HorrorDirector/
│   │   │   │   ├── AI/
│   │   │   │   ├── Items/
│   │   │   │   ├── Puzzles/
│   │   │   │   └── Checkpoints/
│   │   │
│   │   │   ├── Systems/
│   │   │   │   ├── Audio/
│   │   │   │   ├── SaveLoad/
│   │   │   │   ├── SceneManagement/
│   │   │   │   ├── Settings/
│   │   │   │   ├── Input/
│   │   │   │   ├── Accessibility/
│   │   │   │   └── Persistence/
│   │   │
│   │   │   └── Presentation/
│   │   │       ├── HUD/
│   │   │       ├── Menus/
│   │   │       ├── DialogueUI/
│   │   │       ├── Subtitles/
│   │   │       └── Transitions/
│   │   │
│   │   ├── Content/
│   │   │   ├── Scenes/
│   │   │   ├── Prefabs/
│   │   │   ├── Dialogue/
│   │   │   ├── Data/
│   │   │   ├── Audio/
│   │   │   ├── Timeline/
│   │   │   └── Sequences/
│   │   │
│   │   ├── Data/
│   │   │   ├── Definitions/
│   │   │   ├── Configurations/
│   │   │   ├── Input/
│   │   │   └── Localization/
│   │   │
│   │   ├── Prefabs/
│   │   │   ├── Player/
│   │   │   ├── Interactables/
│   │   │   ├── Characters/
│   │   │   ├── UI/
│   │   │   └── Infrastructure/
│   │   │
│   │   ├── Scenes/
│   │   │   ├── Boot/
│   │   │   ├── Frontend/
│   │   │   ├── Gameplay/
│   │   │   └── Development/
│   │   │
│   │   ├── Settings/
│   │   │   ├── RenderPipeline/
│   │   │   ├── Quality/
│   │   │   ├── Lighting/
│   │   │   └── Audio/
│   │   │
│   │   └── ThirdParty/
│   │       └── VendorName/
│   │
│   ├── Editor/
│   ├── Tests/
│   │   ├── EditMode/
│   │   ├── PlayMode/
│   │   └── TestUtilities/
│   ├── Plugins/
│   └── Gizmos/
│
├── Packages/
├── ProjectSettings/
├── Documentation/
│   ├── Architecture/
│   ├── GameDesign/
│   ├── Narrative/
│   ├── Audio/
│   └── Production/
├── Tools/
├── Builds/
├── .gitignore
└── README.md
```
