# 一个轻量级医疗RAG问答系统
# tinychat-lora-medical
基于 Qwen1.5-0.5B 模型加载自训练 LoRA 权重，再用一个医疗问答数据做RAG

LoRA微调只跑了第一轮的3000步，支持从checkpoint继续训练，使用colab T4 1个半小时，损失率大概是0.4

RAG部分可以完全用CPU运行
