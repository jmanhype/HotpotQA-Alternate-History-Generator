# HotpotQA Alternate History Generator

A sophisticated system for creating plausible alternate historical scenarios based on questions from the HotpotQA dataset. This interactive documentation site explains the architecture, algorithms, and implementation details of the system.

## Overview

The HotpotQA Alternate History Generator employs advanced natural language processing techniques and large language models to generate, evaluate, and optimize alternate history narratives. It implements a version of the AFLOW (Automated Flow) Algorithm adapted for historical scenario generation.

## Features

- **Interactive Documentation**: Browse comprehensive system documentation with interactive Mermaid diagrams
- **Audio Narration**: Optional audio narration for enhanced learning experience
- **Responsive Design**: Mobile-friendly interface with dark mode support
- **Visual Architecture**: System architecture diagrams including C4 model and Petri nets

## Key Components

### System Architecture
- **Optimizer**: Manages the entire optimization process
- **Workflow**: Executes the alternate history generation pipeline
- **Evaluator**: Assesses quality based on plausibility, coherence, and historical accuracy
- **Data Loader**: Loads and preprocesses the HotpotQA dataset
- **Configuration Manager**: Manages system configurations

### Workflow Pipeline
1. Historical Fact Extractor
2. Alternate Scenario Generator
3. Plausibility Checker
4. Narrative Coherence Enhancer
5. Historical Accuracy Verifier

## Live Demo

Visit the live documentation site: [HotpotQA Alternate History Generator](https://jmanhype.github.io/HotpotQA-Alternate-History-Generator/)

## Local Development

To view the documentation locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jmanhype/HotpotQA-Alternate-History-Generator.git
   cd HotpotQA-Alternate-History-Generator
   ```

2. Open `index.html` in your web browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```

Alternatively, use a local web server:
```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Diagrams**: Mermaid.js for interactive visualizations
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## Documentation Structure

The documentation covers:
1. **Introduction**: System overview and purpose
2. **System Architecture**: C4 diagrams showing system structure
3. **Key Components**: Detailed component descriptions
4. **AFLOW Implementation**: Algorithm implementation details
5. **Optimization Process**: Recursive optimization workflow
6. **Workflow Execution**: Step-by-step pipeline execution
7. **Prompt Engineering**: LLM prompt design
8. **Performance Evaluation**: Multi-criteria scoring system
9. **Scalability**: Async programming and optimization strategies
10. **Future Improvements**: Roadmap and research directions

## AFLOW Algorithm

The system implements the AFLOW (Automated Flow) Algorithm with:
- **Initialization**: Parameter setup and dataset loading
- **Optimization Loop**: Iterative refinement process
- **Parent Selection**: Top-performing strategy selection
- **Executor Procedure**: Workflow evaluation and scoring

## Performance Evaluation

Generated scenarios are evaluated on:
- **Plausibility Score**: How realistic the alternate scenario is
- **Coherence Score**: Narrative consistency and flow
- **Historical Accuracy Score**: Factual correctness of the scenario

## Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Test thoroughly
5. Commit with clear messages (`git commit -m 'Add feature: description'`)
6. Push to your fork (`git push origin feature/improvement`)
7. Open a Pull Request

See [CLAUDE.md](CLAUDE.md) for AI contribution guidelines.

## License

This project is part of the HotpotQA research initiative. Please cite appropriately if using this work in academic research.

## Related Resources

- [HotpotQA Dataset](https://hotpotqa.github.io/)
- [AFLOW Algorithm Paper](https://arxiv.org/abs/2310.05915)
- [Mermaid Documentation](https://mermaid.js.org/)

## Acknowledgments

This project leverages:
- OpenAI API for language model capabilities
- HotpotQA dataset for training and evaluation
- Mermaid.js for interactive diagrams

## Support

For questions or issues:
- Open an issue on GitHub
- Review the documentation at the live site
- Check the workflow diagrams for system understanding

---

**Note**: This repository contains documentation for the system. For the actual implementation code, please refer to the main project repository.
