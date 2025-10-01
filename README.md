# insurance-agent  保险销售代理人——基于InternLM2.5
 [大模型实战营](https://github.com/InternLM/Tutorial)

## 📢 介绍

**insurance-agent  保险销售代理人** 是一个能够根据给定的保险产品从激发用户购买意愿角度出发进行保险产品解说的保险销售代理人大模型。该代理人能深度理解保险产品特点，具备全面的金融专业知识，通过与客户的互动，了解他们的家庭、健康、财产和未来规划等方面的需求，提供符合其需求的保险产品。

模型用 [xtuner](https://github.com/InternLM/xtuner) 在 [InternLM2](https://github.com/InternLM/InternLM) 的基础上指令微调而来，部署集成了 LMDeploy **加速推理**🚀，支持 **RAG 检索增强生成**📚做到可以随时更新保险规划和建议，还加入带有感情的 **TTS 文字转语音**🔊生成，最后还会**生成代理人数字人视频**🦸，让代理人不止于文字介绍。

**功能点总结：**

- 📜 保险理念导入话术一键生成
- 🚀 KV cache + Turbomind 推理加速
- 📚 RAG 检索增强生成
- 🔊 TTS 文字转语音输出
- 🦸 数字人解说视频生成

## 🎉 NEWS

- [2025.11.10] 重磅发布 数字人 版本
- [2025.11.01] 发布 TTS 版本
- [2025.10.28] 接入 RAG 检索增强
- [2025.10.22] 接入 [LMDeploy](https://github.com/InternLM/lmdeploy)
- [2025.10.18] 发布v1.0模型，完成初版页面
- [2025.10.14] 训练数据准备：保险理念话术、产品介绍话术等
