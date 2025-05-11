# NFL - Node Form Language

This repo powers a Multi-Agent Control Plane in Task Representation.

We use `@NFP~` to define agent roles, instructions, and inert-agent communication.

```nml
@agent: @JITDEV
@action: render_component
@message: "Render a responsive React component from spec."
@context:canvas://landing_v1
payload: {\n  "component": "Hero",
  "style": "modern"
\n}
@end
```

Coming up: https://github.com/JeremiahHorstick/NFL
