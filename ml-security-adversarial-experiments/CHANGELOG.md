# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.0.0] - 2025-11-10

### Added
- Initial release of MNIST adversarial ML project
- Baseline CNN classifier (98.34% clean accuracy)
- FGSM attack implementation (epsilon 2, 4, 8/255)
- FGSM adversarial training defense
- Comprehensive evaluation across multiple epsilon values
- 7 publication-quality visualizations
- Complete documentation (report, README, presentation)
- Fixed seed for reproducibility (seed=42)
- Full results in JSON format
- Removed unneccessary cells on the main notebook

### Results
- Baseline robust accuracy (epsilon=8/255): 24.12%
- Defended robust accuracy (epsilon=8/255): 82.45%
- Improvement: +58.33 percentage points
- Clean accuracy trade-off: -1.56%

### Documentation
- Experiment reports
- Comprehensive README with installation instructions
- Results summary tables
- APA-style references

---

## [Unreleased]

### Planned Features
- PGD attack implementation (stronger multi-step attack)
- Fashion-MNIST evaluation
- CIFAR-10 extension
- Certified defense (randomized smoothing)
- Interactive demo (Gradio/Streamlit)

---

**Note:** Version 1.0.0 represents the complete academic project submission.
Future versions may include extensions and improvements.