<table border="0">
  <tr>
    <td width="200" align="center" valign="top">
      <img src="docs/assets/logo.svg" width="180" alt="{{PROJECT_NAME}} logo">
    </td>
    <td valign="top">
      <h1>{{project_name}}</h1>
      <p><strong>{{TAGLINE}}</strong><br/>
      <em>{{SHORT_DESCRIPTION}}</em></p>
      <p>
        <a href="{{REGISTRY_URL}}"><img src="{{BADGE_VERSION_URL}}" alt="{{REGISTRY_NAME}}"></a>
        <a href="LICENSE"><img src="https://img.shields.io/badge/license-{{LICENSE}}-blue?style=plastic" alt="License {{LICENSE}}"></a>
        <img src="https://img.shields.io/badge/Built%20With-{{LANGUAGE}}-{{LANGUAGE_BADGE_COLOR}}?style=plastic" alt="Built with {{LANGUAGE}}">
        <!-- Add more badges as needed -->
      </p>
    </td>
  </tr>
</table>

---

<p align="center">
  <img src="docs/assets/screenshot.png" alt="{{PROJECT_NAME}} in action" width="900" />
</p>

---

<!--toc:start-->
- [{{project_name}}](#{{project_name}})
  - [Overview](#overview)
  - [{{PROJECT_TYPE_SECTION}}](#{{project_type_section_slug}})
  - [Installation](#installation)
  - [Key Features ({{CURRENT_VERSION}})](#key-features)
  - [Technical Architecture](#technical-architecture)
  - [{{LIFECYCLE_OR_WORKFLOW_SECTION}}](#{{lifecycle_or_workflow_section_slug}})
  - [{{USAGE_OR_API_SECTION}}](#{{usage_or_api_section_slug}})
  - [Roadmap & Milestones](#roadmap--milestones)
  - [Acknowledgments](#acknowledgments)
  - [Contributing](#contributing)
  - [License](#license)
<!--toc:end-->

## Overview

**{{PROJECT_NAME}}** {{OVERVIEW_PARAGRAPH_1}}

{{PROJECT_TYPE_INTRO}}

At its heart lies **`{{CORE_PACKAGE_NAME}}`**, {{CORE_DESCRIPTION}}. Built upon **{{CORE_DEPENDENCY_1}}** and **{{CORE_DEPENDENCY_2}}**, it exposes {{CORE_API_DESCRIPTION}}.

{{PROJECT_TYPE_SPECIFIC_INTRO}}

---

<p align="center">
  <img src="docs/assets/demo.gif" alt="{{PROJECT_NAME}} demo" width="680" />
</p>

---

## {{PROJECT_TYPE_SECTION}}

{{PROJECT_TYPE_SECTION_INTRO}}

{{EMBEDDABLE_OR_STANDALONE_INTRO}}

{{DEPENDENCY_INSTALLATION_BLOCK}}

**Why use `{{CORE_PACKAGE_NAME}}`?**
* **{{BENEFIT_1_TITLE}}:** {{BENEFIT_1_DESCRIPTION}}
* **{{BENEFIT_2_TITLE}}:** {{BENEFIT_2_DESCRIPTION}}
* **{{BENEFIT_3_TITLE}}:** {{BENEFIT_3_DESCRIPTION}}
* **{{BENEFIT_4_TITLE}}:** {{BENEFIT_4_DESCRIPTION}}

---

## Installation

### Via {{PRIMARY_INSTALL_METHOD}} (Recommended)

```{{SHELL_SLUG}}
{{PRIMARY_INSTALL_COMMAND}}
```

### From Source

```{{SHELL_SLUG}}
git clone https://github.com/{{GITHUB_USER}}/{{REPO_NAME}}.git
cd {{REPO_NAME}}
{{BUILD_COMMAND}}
# Binary at: {{BINARY_OUTPUT_PATH}}
```

---

## Key Features ({{CURRENT_VERSION}})

*   **{{FEATURE_1_TITLE}}**: {{FEATURE_1_DESCRIPTION}}
*   **{{FEATURE_2_TITLE}}**: {{FEATURE_2_DESCRIPTION}}
*   **{{FEATURE_3_TITLE}}**: {{FEATURE_3_DESCRIPTION}}
*   **{{FEATURE_4_TITLE}}**: {{FEATURE_4_DESCRIPTION}}
*   **{{FEATURE_5_TITLE}}**: {{FEATURE_5_DESCRIPTION}}
*   **{{FEATURE_6_TITLE}}**: {{FEATURE_6_DESCRIPTION}}
*   **{{FEATURE_7_TITLE}}**: {{FEATURE_7_DESCRIPTION}}

---

## Technical Architecture

{{ARCHITECTURE_INTRO}}

```mermaid
graph TD
    User([{{USER_ACTOR}}]) -->|{{USER_INTERACTION}}| Frontend({{FRONTEND_LABEL}})

    subgraph {{PROJECT_NAME}} Workspace
        Frontend -->|{{INTERNAL_INTERACTION}}| Core({{CORE_LABEL}})

        subgraph Core Engine
            Core --> Component1[{{COMPONENT_1}}]
            Core --> Component2[{{COMPONENT_2}}]
            Component1 --> IO[{{IO_LABEL}}]
            Component2 --> Ext1[{{EXTERNAL_1}}]
            Component2 --> Ext2[{{EXTERNAL_2}}]
        end

        Frontend -.->|{{OPTIONAL_LINK_LABEL}}| SDK({{SDK_LABEL}})
    end

    Ext1 -->|{{EXT1_ACTION}}| Dep1[{{DEPENDENCY_1}}]
    Ext2 -->|{{EXT2_ACTION}}| Dep2[{{DEPENDENCY_2}}]
    Dep1 -.-> Network((Internet))
    IO -.-> Network
    IO --> Disk[(Local Storage)]
```

### Core Components

- **`{{CORE_PACKAGE_NAME}}`**: {{CORE_COMPONENT_DESCRIPTION}}
{{ADDITIONAL_COMPONENTS_BLOCK}}

---

## {{LIFECYCLE_OR_WORKFLOW_SECTION}}

{{LIFECYCLE_OR_WORKFLOW_INTRO}}

```mermaid
stateDiagram-v2
    [*] --> {{STATE_1}} : {{TRIGGER_1}}
    {{STATE_1}} --> {{STATE_2}} : {{TRANSITION_1}}
    {{STATE_2}} --> {{STATE_3}} : {{TRANSITION_2}}
    {{STATE_2}} --> Error : {{ERROR_CONDITION}}

    state {{STATE_3}} {
        [*] --> {{SUBSTATE_1}}
        {{SUBSTATE_1}} --> {{SUBSTATE_2}} : {{SUBTRANSITION_1}}
        {{SUBSTATE_2}} --> [*]
    }

    {{STATE_3}} --> Paused : {{PAUSE_TRIGGER}}
    Paused --> {{STATE_3}} : {{RESUME_TRIGGER}}
    {{STATE_3}} --> Complete : {{SUCCESS_CONDITION}}
    {{STATE_3}} --> Error : {{FAILURE_CONDITION}}
    Error --> {{STATE_1}} : {{RETRY_LOGIC}}
    Complete --> [*]
```

### Key Engineering Decisions

- **{{DECISION_1_TITLE}}:** {{DECISION_1_DESCRIPTION}}
- **{{DECISION_2_TITLE}}:** {{DECISION_2_DESCRIPTION}}
- **{{DECISION_3_TITLE}}:** {{DECISION_3_DESCRIPTION}}

---

## {{USAGE_OR_API_SECTION}}

For a comprehensive breakdown, see the **[Official Docs](docs/wiki/Home.md)**.

{{DOCUMENTATION_LINKS_BLOCK}}

{{USAGE_OR_API_CONTENT_BLOCK}}

---

## Roadmap & Milestones

| Version | Status | Milestone |
| --- | --- | --- |
| **{{V1}}** | ✅ | {{MILESTONE_1}} |
| **{{V2}}** | ✅ | {{MILESTONE_2}} |
| **{{V3}}** | ✅ | {{MILESTONE_3}} |
| **{{V4}}** | ✅ | {{MILESTONE_4}} |
| **{{V5}}** | ⏳ | {{MILESTONE_5}} |
| **{{V6}}** | ⏳ | {{MILESTONE_6}} |

---

## Acknowledgments

- **[{{ACK_1_NAME}}]({{ACK_1_URL}})** — {{ACK_1_DESCRIPTION}}
- **[{{ACK_2_NAME}}]({{ACK_2_URL}})** — {{ACK_2_DESCRIPTION}}

## Contributing

Pull requests are welcome. For major changes, open an RFC issue first. See `CONTRIBUTING.md` for guidelines.

## License

<p align="center">
  Engineered by <a href="https://github.com/{{GITHUB_USER}}">{{AUTHOR_NAME}}</a>.<br>
  Released under the terms of the {{LICENSE}} License.
</p>