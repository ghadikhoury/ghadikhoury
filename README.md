# Ghadi Khoury

AI Engineering student at Penn building software and machine-learning systems, with experience in distributed systems, computer vision, data engineering, and research.

## Featured projects

### [Incident — Distributed-systems incident response](https://github.com/ghadikhoury/incident)

Built a system that detects failures in simulated microservices, correlates AWS CloudWatch alarms, identifies the likely root service, and shows incidents on a live dashboard. It uses FastAPI, React, WebSockets, DynamoDB, Lambda, SQS, and S3. Added a Bedrock diagnosis workflow that gathers bounded evidence and proposes remediation for engineer approval; live model accuracy remains unscored because of an account quota. [Watch the demo](https://github.com/ghadikhoury/incident/blob/main/docs/demo/incident-stage1-demo.mp4) · [Read the evaluation](https://github.com/ghadikhoury/incident/blob/main/docs/STEP9_EVALUATION.md)

### [Flux — Grid-resilience data product](https://github.com/2WKG/flux)

Contributed to a team-built product for exploring **synthetic** energy scenarios. My work spans data ingestion, validation, DuckDB metrics, provenance, reproducible analysis, and interactive visualization, including a data-quality gate that rejects incomplete or mislabeled records. [View my merged pull requests](https://github.com/2WKG/flux/pulls?q=is%3Apr+is%3Amerged+author%3Aghadikhoury)

### [PennAir Shape Detection — Computer vision](https://github.com/ghadikhoury/PennAir-ShapeDetection)

Built an OpenCV pipeline that detects and classifies shapes in noisy video, tracks persistent object IDs and trajectories, and provides demo outputs, a configurable CLI, tests, and CI.

### [Facial Image Classification — ML experiment](https://github.com/ghadikhoury/deep-learning-facial-image-classification)

Compared eight neural-network architectures and transfer-learning approaches on 2,526 images. The selected ResNet50 model reached **83.5% held-out test accuracy** and **0.917 ROC-AUC**. The repository documents dataset and evaluation limits; this is an educational classification experiment, not a diagnostic tool.

## Research experience

At the Prut Lab, optimized a DeepLabCut video-processing pipeline with concurrent FFmpeg workers, reducing processing time from **1 hour 50 minutes to 8.7 minutes per recording day** across 1,329 videos.
