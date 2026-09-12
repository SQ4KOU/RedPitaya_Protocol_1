# Migration audit — Red Pitaya Protocol 1

Migration date: 2026-09-12

Source repository: `SQ4KOU/SQ4KOU-THETIS`
Destination repository: `SQ4KOU/RedPitaya_Protocol_1`

Only project history was migrated. Foreign `.github/workflows/` files were intentionally removed during history filtering because CI definitions are repository-specific. This rewrites destination commit SHAs while retaining the FPGA/ARM/project-source history and commit messages.

| Source branch | Source SHA | Destination branch | Destination SHA |
|---|---|---|---|
| `pavel-20190527-p1` | `400ee47947795d9d5e54b9975c8ae56b4c6b107f` | `reference/pavel-20190527-p1` | `5602a492cd86f896a821a2086109e8707b948fe7` |
| `sq4kou-p1-fpga-arm-confirmed-staging` | `400ee47947795d9d5e54b9975c8ae56b4c6b107f` | `staging/sq4kou-p1-fpga-arm-confirmed` | `5602a492cd86f896a821a2086109e8707b948fe7` |
| `sq4kou-p1-fpga-arm-confirmed` | `da9adaeb4f957df6e1644d44acfe3625766baef5` | `baseline/sq4kou-p1-fpga-arm-confirmed` | `53f7f76cf2332807fbed58a423dfece1dfe28db5` |
| `sq4kou-p1-fpga-arm-confirmed-final` | `70407d32a414bfd15688fac37bf8633edb28ec5c` | `release/sq4kou-p1-fpga-arm-confirmed-final` | `7a6d3d87a754dff5fed9373c1ece9a21f67a8a54` |
| `release-p1-full-sd-v1` | `75b6837cd5cb37d464465935668fb63b32bfdd27` | `release/p1-full-sd-v1` | `d6cc146e6a7430b06b9edbe7750c4fbc6f967673` |

`main` is the project index. Confirmed/release work should be taken from the explicitly named `baseline/` and `release/` branches.
