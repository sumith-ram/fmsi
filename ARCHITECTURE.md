# Architecture and implemented boundaries

Adapted from canonical `docs/ARCHITECTURE_DIAGRAM.md` and the project source/release documentation; this is a newly authored summary.

The implemented default path is React → FastAPI → compact CPU B2 → calibration/review metadata. Speech/ASR and F6 fusion exist in a separate research profile. Research diagrams do not promote those paths to validated moderation. No external queue, cloud deployment or new model is invented. The compact representation preserves the selected decision boundary on the saved test; calibration metadata and review policy are distinct from that classification boundary.

The public-friendly Mermaid diagram is in the [README](README.md). It depicts implemented components, not proposed future infrastructure.

[Return to the case study](README.md).
