# Unreal Engine Developer Tools

A collection of Unreal Engine editor tools by **Rayner Bestard**.

[Portfolio & documentation (English)](https://raynerbest.github.io/tools/) · [Documentación en español](https://raynerbest.github.io/es/tools/)

## Downloads

| Tool | Version | Compatibility | Package |
| --- | --- | --- | --- |
| **Character Debug Tool** | 1.1.0 Beta | Unreal Engine 5.8 | [Download ZIP](./CharacterDebugTool-1.1.0.zip) |
| **Tick Inspector** | 1.1.0 | Unreal Engine 5.8.4 · Windows x64 | [Download ZIP](./TickInspector-1.1.0-UE5.8.4-Win64.zip) |

### Character Debug Tool

Modular real-time character debugging with configurable Data Asset profiles, Gameplay Tag-based metrics, persistent snapshots, TXT/CSV export, and customizable overlay controls.

**Installation:** Extract the `CharacterDebugTool` plugin folder into `<YourProject>/Plugins/`, enable the plugin and its content in Unreal Editor, then open **Tools → Character Debug**. See the [portfolio documentation](https://raynerbest.github.io/tools/#character-debug) for setup and usage.

### Tick Inspector

C++ editor plugin for inspecting and batch-editing primary actor/component Tick configuration, navigating to owners, highlighting bounds, exporting CSV, and capturing attributed Tick CPU samples during PIE.

**Installation:** Extract the `TickInspector` plugin folder into `<YourProject>/Plugins/` so `TickInspector.uplugin` is directly inside the folder. Restart Unreal Editor and open **Tools → Tick Inspector**. Prebuilt binaries target **UE 5.8.4 on Windows x64**; other engine builds require recompiling the included C++ source. See the [portfolio documentation](https://raynerbest.github.io/tools/#tick-inspector).

## Notes

- These ZIP packages are public distributions. Development projects and internal repositories are maintained separately.
- Tick Inspector CPU captures measure attributable synchronous primary-Tick scopes in PIE, not the total cost of an actor or its GPU work.
- Please consult each tool's compatibility and limitations before using it in a production project.

© 2026 Rayner Bestard
