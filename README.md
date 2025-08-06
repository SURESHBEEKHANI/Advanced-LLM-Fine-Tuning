# Advanced LLM Fine-Tuning

A comprehensive repository for fine-tuning large language models (LLMs) using state-of-the-art techniques and diverse datasets. This project provides a complete framework for experimenting with various fine-tuning approaches including LoRA, QLoRA, full fine-tuning, and instruction tuning.

## 🚀 Features

- **Multiple Fine-tuning Techniques**: Support for LoRA, QLoRA, full parameter fine-tuning, and PEFT methods
- **Diverse Model Support**: Compatible with popular models like Llama 2/3, Mistral, GPT, BERT, and more
- **Data Processing Pipeline**: Automated data preprocessing and validation workflows
- **Evaluation Framework**: Comprehensive evaluation metrics and benchmarking tools
- **Distributed Training**: Multi-GPU and distributed training capabilities
- **Experiment Tracking**: Integration with Weights & Biases, TensorBoard, and MLflow
- **Production Ready**: Model deployment and serving configurations


## 📊 Supported Models

| Model Family | Sizes | Fine-tuning Methods | Status |
|-------------|-------|-------------------|---------|
| Llama 2 | 7B, 13B, 70B | LoRA, QLoRA, Full | ✅ |
| Llama 3 | 8B, 70B | LoRA, QLoRA, Full | ✅ |
| Mistral | 7B, 8x7B | LoRA, QLoRA, Full | ✅ |
| CodeLlama | 7B, 13B, 34B | LoRA, QLoRA, Full | ✅ |
| Falcon | 7B, 40B | LoRA, QLoRA | ✅ |
| MPT | 7B, 30B | LoRA, QLoRA | 🚧 |
| Phi-3 | 3.8B, 14B | LoRA, QLoRA | 🚧 |




This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Hugging Face Transformers](https://github.com/huggingface/transformers)
- [PEFT Library](https://github.com/huggingface/peft)
- [Alpaca Dataset](https://github.com/tatsu-lab/stanford_alpaca)
- [LoRA Paper](https://arxiv.org/abs/2106.09685)
- [QLoRA Paper](https://arxiv.org/abs/2305.14314)


---

**Made with ❤️ by the LLM Fine-tuning Community**
