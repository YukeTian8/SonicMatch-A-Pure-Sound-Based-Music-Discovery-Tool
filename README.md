# SonicMatch · A Pure Sound-Based Music Discovery Tool

Discover music through sound, not metadata.

## What is SonicMatch?

SonicMatch is a lightweight music recommendation tool that analyzes pure audio content—timbre, rhythm, spectral texture—and matches sonically similar songs, with zero reliance on metadata, genres, or user history.

## Why it matters

Traditional recommendation systems rely heavily on collaborative filtering or labeled metadata. But what if users only care about how a song sounds? SonicMatch redefines music discovery by offering a new way to explore sonic similarities directly from raw audio features.

## How it works

- Extract mel spectrograms from audio previews
- Encode timbral and rhythmic features using a Time-Frequency Autoencoder
- Project audio embeddings into a 2D space using UMAP
- Use cosine similarity to recommend sound-alike tracks

## Tech Stack

- Python
- Librosa
- TensorFlow / Keras
- UMAP
- Spotify Web API

## Try it out

Main_Notebook.ipynb

1. Load and preprocess audio
2. Train the autoencoder
3. Visualize audio embeddings
4. Query recommendations

## Acknowledgement

This project is adapted and restructured from open-source implementations. All architectural decisions, evaluations, and visualizations were independently designed and refined during the author's personal research process.

---

# SonicMatch · 一个纯基于声音的音乐探索工具

通过声音而非标签发现音乐。

## 什么是 SonicMatch？

SonicMatch 是一个轻量级音乐推荐工具，完全基于音频内容本身（如音色、节奏、频谱纹理）来匹配声音相似的歌曲，完全不依赖标签、风格分类或用户听歌历史。

## 为什么有意义？

传统音乐推荐系统通常依赖协同过滤或人工标注的元数据。但当用户只关注“声音本身”时，SonicMatch 提供了一种全新的探索方式：仅通过声音的数学相似性进行音乐发现。

## 系统原理

- 从音频预览中提取 Mel 频谱图
- 使用时频自编码器编码音色与节奏特征
- 通过 UMAP 将嵌入映射到二维空间
- 基于余弦相似度推荐声音相近的音乐

## 技术栈

- Python
- Librosa
- TensorFlow / Keras
- UMAP
- Spotify Web API

## 快速体验

Main_Notebook.ipynb

1. 读取并预处理音频
2. 训练自编码器模型
3. 可视化音频嵌入空间
4. 执行推荐查询

## 致谢说明

本项目在已有开源方案基础上进行改写与结构优化，所有架构设计、评估方式与可视化步骤均为作者在个人研究过程中独立完成与改进。
