Implementation of top-down parser for the following grammar:
⟨program⟩ → ⟨class def list⟩ ⟨fun def list⟩
⟨class def list⟩ → ε | ⟨class def⟩ ⟨class def list⟩
⟨class def⟩ → "class" ⟨class name⟩ ⟨class body⟩
⟨class name⟩ → ⟨id⟩
⟨class body⟩ → "{" ⟨field var list⟩ "}"
⟨field var list⟩ → ε | ⟨field var⟩ ⟨field var list⟩
⟨field var⟩ → ⟨id⟩ 