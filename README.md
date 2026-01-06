# Shed AI Infrastructure

This is the main repository for the Shed AI platform, containing all core components as git submodules.

## Components

- **3d-builder/** - The 3D Builder application (MyShed-3D / ShedAi-3D)
- **admin-dashboard/** - Admin Dashboard for managing the platform
- **backend/** - Backend API services (blacksbuilding-be)

## Getting Started

Clone this repository with all submodules:

```bash
git clone --recurse-submodules https://github.com/ShedAiApp/Shed-AI.git
```

Or if you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To pull the latest changes from all submodules:

```bash
git submodule update --remote --merge
```

## Railway Deployment

Railway project: https://railway.com/project/a53fccf2-67ae-434c-90ac-9bb3d8188a21

## Repository Links

- [ShedAi-3D](https://github.com/ShedAiApp/ShedAi-3D)
- [ShedAi-Admin](https://github.com/ShedAiApp/ShedAi-Admin)
- [ShedAi-Backend](https://github.com/ShedAiApp/ShedAi-Backend)
