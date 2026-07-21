# Sakku — Codex Desktop Pet

Sakku is a clean, tailless chibi 2D companion wearing gray cat-ear headphones. The pet includes idle, directional running, interaction, success, failure, waiting, active-task, and review animations.

## Preview

| State | Preview |
| --- | --- |
| Idle | ![Idle](previews/idle.gif) |
| Running right | ![Running right](previews/running-right.gif) |
| Running left | ![Running left](previews/running-left.gif) |
| Touch | ![Touch](previews/touch.gif) |
| Sakura hover | ![Sakura hover](previews/success.gif) |
| Failed | ![Failed](previews/failed.gif) |
| Waiting for permission | ![Waiting](previews/waiting.gif) |
| Active task | ![Active task](previews/running.gif) |
| Review | ![Review](previews/review.gif) |

## Package

The Petdex-compatible package consists of:

```text
pet.json
spritesheet.webp
```

The spritesheet is a transparent `1536 × 1872` WebP using the Codex Desktop 8-column × 9-row animation atlas format.

## Manual installation

Copy `pet.json` and `spritesheet.webp` into:

```text
<CODEX_HOME>/pets/sakku/
```

Restart Codex Desktop, then select Sakku under **Settings → Appearance → Pets**.

## Petdex installation

After the pet has been approved in the Petdex gallery:

```powershell
npx.cmd petdex install sakku
```

## License

No reuse license has been selected yet. Add a `LICENSE` file before public distribution so users know what they may do with the character and artwork.
