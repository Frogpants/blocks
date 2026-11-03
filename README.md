# blocks

Suggested folder layout for a C++ game engine that supports both block-based and text-based programming:

```text
.
├── engine/
│   ├── include/        # Public engine headers
│   └── src/            # Engine implementation (C++)
├── editor/
│   ├── blocks/         # Block editor UI and tooling
│   └── text/           # Text editor/IDE integration
├── scripting/
│   ├── blocks/         # Block schemas, node definitions, serialization
│   └── text/           # Text language integration (parser/bindings)
├── assets/
│   ├── blocks/         # Block editor assets
│   ├── scripts/        # Script samples/templates
│   └── shaders/        # Rendering shader assets
├── tests/
│   ├── unit/           # Unit tests
│   └── integration/    # End-to-end engine/editor tests
└── tools/
    ├── build/          # Build and packaging helper tooling
    └── content/        # Asset/content pipeline tools
```
