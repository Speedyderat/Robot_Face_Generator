# Robot_Face_Generator
This is a tool that can generate robot faces using Image Generation AI.
The tool is built around the HuggingFace🤗 Diffusers [1] library. This library can be used to access a wide variety of AI models available on the HuggingFace🤗 website [2]. The tool uses an Image Generation Model called "stable-diffusion-v1-5" [3] by runwayml.
The tool is still a work in progress and is subjected to change. It is currently built within Jupyter Notebook using Python, as this allows the file to be ran off a webserver. This is necessary as the tool requires large amounts of computational power, something a simple laptop is not able to handle. Future development might enable for a standalone application.

[1] https://huggingface.co/docs/diffusers/index
[2] https://huggingface.co/
[3] https://huggingface.co/runwayml/stable-diffusion-v1-5
