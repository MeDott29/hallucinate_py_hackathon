# Hallucinate Presentation Generator

This script generates a PowerPoint presentation for the Hallucinate project, an edge-first MLOPS framework for decentralized AI.

## Features

- Creates an 8-slide presentation covering:
  - Project overview
  - Technical challenges
  - Architecture design
  - Key modules
  - Implementation details
  - Future development
- Includes SVG visualizations for:
  - Datacenter vs Edge computing comparison
  - System architecture diagram

## Requirements

- Python 3.7+
- python-pptx
- Pillow

## Installation

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the script:
```bash
python create_presentation.py
```

This will generate `hallucinate_presentation.pptx` in the current directory.

## SVG Assets

The presentation includes two SVG diagrams:
- `datacenter_vs_edge.svg`: Illustrates the difference between traditional datacenter and edge computing
- `architecture.svg`: Shows the three-layer architecture of the Hallucinate system

Note: The current implementation uses placeholder shapes for SVGs. In a production environment, you would want to convert SVGs to PNG/JPEG for proper PowerPoint integration.

## Customization

You can modify the content by editing the `create_presentation.py` script. Key areas for customization:
- Slide content and structure
- Visual styling
- Contact information
- SVG diagrams

## License

MIT License