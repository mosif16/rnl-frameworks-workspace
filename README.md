# Record and Learn Frameworks Workspace

This directory is a mono workspace that indexes all reusable frameworks.
Each framework is an independent public GitHub repository.

## Structure
- `tool-list.yaml` -> canonical framework catalog
- `packages/` -> Git submodules pointing to each public framework repository
- `scripts/` -> setup and maintenance scripts

## Framework Repositories (public)
- `rnl-learning-domain-kit`
- `rnl-core-utilities-kit`
- `rnl-rag-kit`
- `rnl-sync-core-kit`
- `rnl-cloudkit-adapter-kit`
- `rnl-ai-generation-kit`
- `rnl-capture-live-kit`
- `rnl-voice-practice-kit`
- `rnl-coaching-kit`
- `rnl-gamification-core-kit`
- `rnl-monetization-kit`
- `rnl-study-planning-kit`

## Usage
- To clone with all frameworks:
  - `git clone --recurse-submodules <workspace-repo-url>`
- To refresh all framework submodules:
  - `git submodule update --init --recursive --remote`
