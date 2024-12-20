![Smol](https://github.com/merveenoyan/smol-vision/assets/53175384/930d5b36-bb9d-4ab6-8b5a-4fec28c48f80)
# Smol Vision 🐣
Recipes for shrinking, optimizing, customizing cutting edge vision and multimodal AI models. 

Latest examples 👇🏻 
- [Multimodal RAG using ColPali and Qwen2-VL](https://github.com/merveenoyan/smol-vision/blob/main/ColPali_%2B_Qwen2_VL.ipynb)
- [Fine-tune ColPali for Multimodal RAG](https://github.com/merveenoyan/smol-vision/blob/main/Finetune_ColPali.ipynb)                                                                         

**Note**: The script and notebook are updated to fix few issues related to QLoRA!

|                              | Notebook                                                                                                                                                                | Description                                                                                                |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Quantization/ONNX            | [Faster and Smaller Zero-shot Object Detection with Optimum](https://github.com/merveenoyan/smol-vision/blob/main/Faster_Zero_shot_Object_Detection_with_Optimum.ipynb) | Quantize the state-of-the-art zero-shot object detection model OWLv2 using Optimum ONNXRuntime tools.      |
| VLM Fine-tuning              | [Fine-tune PaliGemma](https://github.com/merveenoyan/smol-vision/blob/main/Fine_tune_PaliGemma.ipynb)                                                                   | Fine-tune state-of-the-art vision language backbone PaliGemma using transformers.                          |
| Intro to Optimum/ORT         | [Optimizing DETR with 🤗 Optimum](https://github.com/merveenoyan/smol-vision/blob/main/Reduce_any_model_to_fp16_using_%F0%9F%A4%97_Optimum_DETR.ipynb)                   | A soft introduction to exporting vision models to ONNX and quantizing them.                                |
| Model Shrinking              | [Knowledge Distillation for Computer Vision](https://huggingface.co/docs/transformers/en/tasks/knowledge_distillation_for_image_classification)                         | Knowledge distillation for image classification.                                                           |
| Quantization                 | [Fit in vision models using Quanto](https://github.com/merveenoyan/smol-vision/blob/main/Fit_in_vision_models_using_quanto.ipynb)                                       | Fit in vision models to smaller hardware using quanto                                                      |
| Speed-up                     | [Faster foundation models with torch.compile](https://github.com/merveenoyan/smol-vision/blob/main/Faster_foundation_models_with_torch_compile.ipynb)                   | Improving latency for foundation models using `torch.compile`                                              |
| VLM Fine-tuning     | [Fine-tune Florence-2](https://github.com/merveenoyan/smol-vision/blob/main/Fine_tune_Florence_2.ipynb)                                                                          | Fine-tune Florence-2 on DocVQA dataset                                                                |
| VLM Fine-tuning    | [QLoRA/Fine-tune IDEFICS3 or SmolVLM on VQAv2](https://github.com/merveenoyan/smol-vision/blob/main/Smol_VLM_FT.ipynb)                                                                          | QLoRA/Full Fine-tune IDEFICS3 or SmolVLM on VQAv2 dataset                                                                 |
| VLM Fine-tuning (Script)   | [QLoRA Fine-tune IDEFICS3 on VQAv2](https://github.com/merveenoyan/smol-vision/blob/main/smolvlm.py)                                                                          | QLoRA/Full Fine-tune IDEFICS3 or SmolVLM on VQAv2 dataset                                                                 |
| Multimodal RAG    | [Multimodal RAG using ColPali and Qwen2-VL](https://github.com/merveenoyan/smol-vision/blob/main/ColPali_%2B_Qwen2_VL.ipynb)                                                                          | Learn to retrieve documents and pipeline to RAG without hefty document processing using ColPali through Byaldi and do the generation with Qwen2-VL                                                              |
| Multimodal Retriever Fine-tuning    | [Fine-tune ColPali for Multimodal RAG]([https://github.com/merveenoyan/smol-vision/blob/main/ColPali_%2B_Qwen2_VL.ipynb](https://github.com/merveenoyan/smol-vision/blob/main/Finetune_ColPali.ipynb))                                                                          | Learn to apply contrastive fine-tuning on ColPali to customize it for your own multimodal document RAG use case                                                              |
| Speed-up/Memory Optimization | Vision language model serving using TGI (SOON)                                                                                                                          | Explore speed-ups and memory improvements for vision-language model serving with text-generation inference |
| Quantization/Optimum/ORT     | All levels of quantization and graph optimizations for Image Segmentation using Optimum (SOON)                                                                          | End-to-end model optimization using Optimum                                                                |
