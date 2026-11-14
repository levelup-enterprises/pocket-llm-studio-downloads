# Pocket LLM Studio Downloads

Official installer downloads for **Pocket LLM Studio Companion**, the Windows desktop companion for chatting with a local AI model and editing project files from your computer or a paired phone.

This repository distributes installers through **GitHub Releases**. It does not contain the application's source code.

## Download and install

1. Open this repository's **Releases** section.
2. Select the latest published release.
3. Under **Assets**, download the Windows installer ending in `.exe`, not the automatically generated source-code archives.
4. Run the installer and open **LLM View Companion**.

The installer includes its own application runtime. You do not need to install Node.js or npm.

## Requirements

- Windows x64.
- LM Studio with a loaded model and its OpenAI-compatible API server enabled. Model-driven file edits require a model that supports tool calling.
- An existing project folder you explicitly choose to share.

For remote access, configure a relay and pair your phone with approval on the computer. Keep the companion open and the computer awake. Do not expose the model API directly to the internet.

## Preview notice

Pocket LLM Studio is an early preview. Current Windows installers are unsigned, so Windows may display an unknown-publisher or SmartScreen warning. Install only releases you trust.

Back up important projects before allowing a model to edit files. Share only intended project folders, not folders containing credentials or other sensitive information.
