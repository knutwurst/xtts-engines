# XTTS Studio Pro — Engine Model Mirror

Public mirror of TTS engine model files used by **XTTS Studio Pro**.

This mirror exists to ensure long-term availability of the engine checkpoints
even if upstream sources change, become gated, get rate-limited, or are taken
down. The app can be configured (see *Diagnose → Modell-Quelle*) to download
either from the original upstream or from this mirror; the default is mirror.

All files are distributed via **GitHub Releases**. Each release contains:

- The original model files, unmodified, byte-for-byte identical to upstream.
- A `SHA256SUMS` manifest for integrity verification.
- A `LICENSE` and `ATTRIBUTION` file copied from the original source.

## Engines

| Release tag | Original source | License |
|---|---|---|
| `openaudio-s1-mini-v1.0` | [fishaudio/openaudio-s1-mini](https://huggingface.co/fishaudio/openaudio-s1-mini) | CC-BY-NC-SA-4.0 |
| `fish-speech-1.5` *(planned)* | [fishaudio/fish-speech-1.5](https://huggingface.co/fishaudio/fish-speech-1.5) | CC-BY-NC-SA-4.0 |
| `xtts-v2.0.3` *(planned)* | [coqui/XTTS-v2](https://huggingface.co/coqui/XTTS-v2) | Coqui Public Model License (CPML) |
| `chatterbox-v0.1` *(planned)* | [ResembleAI/chatterbox](https://huggingface.co/ResembleAI/chatterbox) | MIT |
| `zonos-v0.1-transformer` *(planned)* | [Zyphra/Zonos-v0.1-transformer](https://huggingface.co/Zyphra/Zonos-v0.1-transformer) | Apache-2.0 |

## Attribution

All models remain the intellectual property of their respective authors. The
files in this mirror are unmodified copies; this repository adds no derivative
work to the model weights themselves. See each release's `LICENSE` /
`ATTRIBUTION` files for the original copyright notice and license text.

## Non-commercial use

Some of the mirrored models (notably anything from Fish Audio and Coqui XTTS)
are licensed for **non-commercial use only**. By downloading from this mirror
you accept the same terms as the upstream license. XTTS Studio Pro itself is a
non-commercial project.
