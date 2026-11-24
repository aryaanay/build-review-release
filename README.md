# Build, review, and release

A Codex skill for turning a creation brief into a tested project and checking
that it is ready to publish. It covers planning, skill selection, end-to-end
checks, accessibility and visual review for interfaces, and GitHub release
verification.

To use it across local Codex projects, copy the folder into
`$CODEX_HOME/skills/build-review-release`. To share it with a project, place it
under that repository's `.agents/skills/` directory. In a new chat, ask Codex to
use `$build-review-release` with your project brief.

The skill has no runtime dependencies. It uses tools already available in
your workspace and follows the publication permissions and budget in your brief.
