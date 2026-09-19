# Video Intelligence

## Video Intelligence Discovery Lab

**From hypothesis to evidence.**

What if a company could test a new video intelligence capability before investing in a full product or infrastructure build? Video Intelligence is a public demonstration of a discovery-lab pattern for turning video into measurable evidence.

```text
Hypothesis → Experiment → Measurement → Evidence → Decision
```

## Demonstrated capabilities

- **Perception:** object detection with YOLO.
- **Flow Intelligence:** tracking with ByteTrack and event metrics.
- **Semantic Video Search:** CLIP embeddings, Qdrant retrieval and `recall@k` diagnostics.

## Demonstration results

| Experiment | Evidence | Status |
|---|---:|---|
| Flow Intelligence | 62 frames · 55 tracks · 2,377 events | Demonstrated |
| Semantic Video Search | 499 indexed objects · 100% Recall@10 on 3 diagnostic queries | Demonstrated |

These results use public proxy footage and are demonstrations of capability, not claims about any specific client environment.

## Architecture

```text
Video → Detection → Tracking → Events → Representation → Evaluation → Decision
```

See [`docs/architecture.md`](docs/architecture.md) for the design and [`docs/experiments.md`](docs/experiments.md) for the public experiment cards. The private implementation, sensitive registries and client-specific hypotheses are intentionally not included here.

## Reproducibility and licenses

The public repository contains explanatory material and sanitized examples. It does not redistribute model weights, datasets or third-party video. Fetch external dependencies and data according to their respective licenses. Review the terms of Ultralytics, OpenCLIP, Qdrant and each dataset before commercial use.
