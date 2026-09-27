# NLOS-OCC: Non-Line-of-Sight Optical Camera Communication

A comprehensive research survey project on Non-Line-of-Sight Optical Camera Communication (NLOS-OCC), covering the physical layer, signal recovery, hardware, networking, applications, and emerging directions including event cameras, UAV OCC, underwater OCC, semantic optical communication, and retroreflective ISAC.

## Project Structure

```
NLOS-OCC/
├── latex/                          # LaTeX survey articles and bibliography
│   ├── main.tex                    # Main NLOS-OCC survey (16 research points, 6 layers)
│   ├── main.pdf                    # Compiled PDF (12 pages)
│   ├── refs.bib                    # Main bibliography (36 entries)
│   ├── event_nlos_survey.tex       # Event camera NLOS communication survey
│   ├── event_nlos_survey.pdf       # Compiled PDF (8 pages)
│   ├── event_nlos_refs.bib         # Event camera bibliography (17 entries)
│   └── NLOS-OCC_文献综述.md        # Chinese literature review notes
├── pdfs/                           # Downloaded paper PDFs (open access)
│   ├── neuromorphic_nlos_owc_arXiv2503.11226.pdf
│   └── event2024motion_arXiv2412.00816.pdf
├── codes/                          # Cloned open-source code repositories
│   ├── EventOCC/                   # Motion-Aware OCC with Event Cameras (RAL 2024)
│   ├── Event-Beacon-Communication/ # Smart Visual Beacons (IROS 2022)
│   ├── Prometheus/                 # iOS screen-to-camera OCC
│   ├── optical-camera-communication/
│   ├── python-vlc-rolling/         # CSK rolling shutter VLC simulation
│   ├── rs-vlc-model/               # NLOS rolling shutter VLC model
│   ├── VLCDetector/                # Android rolling shutter VLC
│   └── README.md                   # Code repo documentation
└── README.md                       # This file
```

## Survey Framework

The main survey organizes NLOS-OCC research into a **6-layer framework with 16 research points**:

| Layer | Research Points | Focus |
|-------|----------------|-------|
| Physical (RP1-3) | Channel modeling, modulation, coding | BRDF, OOK/CSK/N-pulse, Raptor/RaptorQ |
| Signal Recovery (RP4-6) | Denoising, deep learning, event cameras | U-Net, GAN, event-camera OCC |
| Hardware (RP7-8) | Smartphone OCC, RIS | Pro mode, RAW domain, ORIS |
| Network (RP9-10) | MIMO, heterogeneous fusion | WDM-MIMO, NOMA, VLC+RF |
| Applications (RP11-12) | V2V/V2I, IoT/ISAC | Vehicular, indoor VLP |
| Emerging (RP13-16) | UAV, underwater, semantic, RO-ISAC | New frontiers |

## Event Camera NLOS Survey

A focused survey tracing the technical evolution of event cameras for NLOS communication through **four developmental stages**:

1. **Stage 1 (2017-2018)**: Proof-of-concept event-OCC (500 bit/s → 16 kbit/s)
2. **Stage 2 (2022-2024)**: Spatial encoding and beacon systems (100m range)
3. **Stage 3 (2025)**: First NLOS event-camera demonstrations (passive reflections)
4. **Stage 4 (2025-2026)**: Long-range outdoor (80 kbit/s @ 320m) and specialized deployments

## Building the PDFs

```bash
cd latex
pdflatex main.tex && bibtex main && pdflatex main.tex && pdflatex main.tex
pdflatex event_nlos_survey.tex && bibtex event_nlos_survey && pdflatex event_nlos_survey.tex && pdflatex event_nlos_survey.tex
```

Requires TeX Live 2024 or later.

## License

This is a research survey project. Individual paper copyrights belong to their respective authors. The survey text is provided for academic reference.
