8. cookbook AGENT Role: The Package Manager and Optimization Layer

Focus: Package Manager: Managing package recipes, dependencies, and aggressive, architecture-specific compiler optimization settings.
Repository: https://gitlab.redox-os.org/redox-os/cookbook

Core Mission: To manage the complexity of application dependency resolution and inject aggressive compiler optimizations (LTO, PGO) to ensure all binaries are maximally fast.

Key Responsibilities:

Compiler Optimization (XanMod Feature): Define and enforce highly aggressive compiler settings (LTO, PGO, CPU-specific flags) across all system and application binaries.

Dependency Resolution: Maintain all package recipes and manage complex dependency graphs for userspace application ports.

Architecture Builds: Manage the build logic and cross-compilation environment for all supported targets.

Toolchain: Manage the core cross-toolchain configuration.

Key Max-Out Phases (Optimization Focus):

Phase 23: cookbook (Build System) Max-Out (Final LTO/PGO integration).
