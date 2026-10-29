# Component workbench contract

Choose the mode needed by the task. Do not create a scratch route after every small edit.

| Mode | What it answers | Evidence |
| --- | --- | --- |
| States | What does the real component render in each reachable state? | Existing branches, actual data seam and rendered fixtures |
| Stress | What breaks under applicable hostile inputs? | Rendered observations, not predictions |
| Variants | Which answer to a named design question is preferred? | Full-size alternatives in their real context |

## State and stress setup

Record the component's production path, import, providers, container and actual input seam. Feed fixtures through props or the existing cache, provider or request boundary. Reuse the real component without copying or restyling it.

Enumerate only reachable states. Missing implementation is a gap, not a demonstrated state. Hold loading and pending fixtures until the switcher changes them. Record dropped scenario axes and why they do not apply.

Stress only plausible inputs. Uncontrolled text may need long strings or mixed-direction content. Repeated data may need zero, one and many items. A fixed icon need not receive invented text. Record the action and visible result for each tested case.

Keep scratch routes and fixtures isolated from production imports and live data. Label them as test data. Record one removal boundary. Preserve them until their owner is finished; cleanup is not permission to delete unrelated files.

## Variant comparison

Record one primary question and axis, such as grouping, density, emphasis, typography or wording. Keep content, task, identity and functional requirements consistent. Show the component full-size with the surrounding page.

Record dependent differences. A density change that requires smaller type is a package comparison, not proof that spacing alone caused the preference.

Capture the chosen artifact version, exact detail, reason, medium and scope through the existing taste system. A selected variant does not become a universal style. Agent judgments remain separate from human choices.

## Report

Name the source version, scenarios, performed actions, observations, skipped checks and owning brief or component. A workbench is not a quality certificate. A predicted break is a test hypothesis until observed.

Adapted from Jakub Krehel's state-machine, break and variant methods at 592aedc44d7d5b3e29740984252902f3e5402a1c. The original MIT notice remains in LICENSE. This file is a Rampart addition.
