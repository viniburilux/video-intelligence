# Public architecture

## Applied Intelligence

Applied Intelligence is an experimental infrastructure for applied engineering and R&D. It starts with an operational problem, the available context and data, and investigates which technological path is worth developing.

```text
Problem → Hypothesis → Experiment → Evidence → Decision → System
```

Experimentation is not the end state. The purpose of an experiment is to produce enough evidence to decide whether a mechanism should be developed further, reframed, or abandoned.

## Demonstrated capability: Video Intelligence

The public video capability presents a small, reusable pipeline: inspect a video, detect objects, maintain tracks, convert observations into an Event Schema, optionally create visual embeddings, search by text, and record evidence in an Experiment Card.

```text
Video → Detection → Tracking → Events → Representation → Evaluation → Decision
```

The implementation details represented by the public evidence include YOLO for detection, ByteTrack for tracking, CLIP embeddings, Qdrant retrieval, event metrics, and diagnostic evaluation. These are instruments of the demonstrated capability, not a fixed product boundary for Applied Intelligence.

The public layer is intentionally a demonstration, not the complete private laboratory. Other data modalities may be investigated when a problem, context and representative data justify them; this repository does not claim that every modality is already implemented.
