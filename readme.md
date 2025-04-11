# Book2PPT: AI-Powered eBook to Presentation Converter

## Overview

Book2PPT is an intelligent tool that converts eBook content into well-structured PowerPoint presentations. This project leverages AI technologies to analyze text content, extract key information, and generate visually appealing slides automatically.

## Problem Statement

Reading lengthy eBooks or documents and manually creating presentations from them is time-consuming and tedious. Book2PPT solves this problem by automatically processing eBook content and transforming it into concise, informative slides that capture the essence of the original material.

## Key Features

- **Intelligent Content Extraction**: Identifies key concepts, main points, and important details from eBooks
- **Automatic Slide Generation**: Creates well-structured PowerPoint presentations with appropriate layouts
- **Image Integration**: Extracts and incorporates relevant images from the source material
- **Customizable Templates**: Offers various presentation styles and templates
- **Multi-format Support**: Works with popular eBook formats (PDF, EPUB, MOBI, etc.)
- **Text Summarization**: Uses AI to condense lengthy paragraphs into concise bullet points
- **Smart Organization**: Maintains the logical flow and hierarchy of information

## AI Technologies Used

- Natural Language Processing (NLP) for content analysis and understanding
- Text summarization algorithms to extract key information
- Computer Vision for image extraction and processing
- Machine Learning for layout optimization and content organization

## Installation

```bash
git clone https://github.com/yourusername/book2ppt.git
cd book2ppt
pip install -r requirements.txt
```

## Usage

```bash
python book2ppt.py --input your-ebook.pdf --output presentation.pptx --template business
```

## Command Line Arguments

- `--input`: Path to the input eBook file
- `--output`: Desired output filename for the PowerPoint
- `--template`: Presentation template (default, business, academic, etc.)
- `--summary-level`: Depth of summary (brief, moderate, detailed)
- `--include-images`: Whether to extract and include images (true/false)

## How It Works

1. **Content Extraction**: The system parses the eBook to extract text and images
2. **Content Analysis**: AI algorithms analyze the text to identify key topics, important points, and the hierarchical structure
3. **Summarization**: NLP models summarize lengthy content into concise points
4. **Slide Generation**: The system creates slides with appropriate layouts based on content type
5. **Visual Enhancement**: Images are included, and visual elements are added to improve engagement

## Requirements

- Python 3.8+
- PowerPoint or compatible presentation software
- Dependencies listed in requirements.txt

## Project Structure

```
book2ppt/
├── book2ppt.py         # Main script
├── extractors/         # Content extraction modules
├── analyzers/          # Text analysis components
├── generators/         # Slide generation logic
├── templates/          # Presentation templates
├── utils/              # Utility functions
└── models/             # AI model files
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Libraries used: python-pptx, PyPDF2, NLTK, spaCy, etc.
- Research papers on text summarization and information extraction

## Future Enhancements

- Interactive mode for customizing slides during generation
- Web interface for easier usage
- Cloud-based processing for larger documents
- Support for additional languages
- Integration with citation management tools
