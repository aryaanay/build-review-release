# Choosing tools for a build

Use the tools that match the project and record what each one verified. Recheck
upstream documentation, applicability, and costs before adding a dependency.

| Resource | When it fits |
| --- | --- |
| Hallmark | Art direction, design references, and visual review for new pages. Use reviewed local helpers. Leave paid image generation and global hooks disabled under a zero-cost brief. |
| Apple Design | Gestures, interruptible motion, depth, typography, and reduced-motion behavior. |
| Scroll Craft | Optional reference for a deliberately scroll-driven experience. Use authorized local assets and reviewed local helpers. |
| Watermelon UI | React components, blocks, and dashboards. |
| Motion Primitives | Focused React and Motion interactions. |
| Kokonut UI | Free React components for AI interfaces. Check the individual component's license and tier. |
| Bklit UI | React charts and data visualization. |
| Anime.js | Timeline-driven animation when native CSS or existing motion tooling is insufficient. |
| Defensive security review | Review owned code for validation, trust boundaries, dependency risk, and fixes. Use ordinary control tests. Keep exploit development and autonomous offensive workflows out of scope. |

Official references: [Hallmark](https://github.com/nutlope/hallmark),
[Watermelon UI](https://ui.watermelon.sh/),
[Motion Primitives](https://motion-primitives.com/),
[Kokonut UI](https://kokonutui.com/), [Bklit UI](https://ui.bklit.com/), and
[Anime.js](https://animejs.com/documentation/).
