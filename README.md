# Chinese-LlaMA2

<p align="center">
    <br>
    <img src="./assets/chinese-llama2-banner.png" width="600"/>
    <br>
</p>
<p align="center">
    <img alt="GitHub" src="https://img.shields.io/github/license/ymcui/Chinese-LLaMA-Alpaca.svg?color=blue&style=flat-square">
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/ymcui/Chinese-LLaMA-Alpaca">
</p>

就在不久前，Meta最新开源了Llama 2模型，完全可商用，看来Meta势必要与OpenAI (ClosedAI) 硬刚到底。虽然Llama 2对原版的LlaMA模型做了升级，但是其仍然对中文没有太好的支持，需要在中文上做定制化。所以我们决定在次开展Llama 2的中文汉化工作：
- ⏳[Chinese-LlaMA2](https://huggingface.co/michaelwzhu/Chinese-LlaMA2-7B): 对Llama 2进行中文预训练；
  - 第一步：先在5.2G中文预料上进行训练；后续将会加大训练规模 
- ⏳[Chinese-LlaMA2-chat](https://huggingface.co/michaelwzhu/Chinese-LlaMA2-7B-chat): 对[Chinese-LlaMA2](https://huggingface.co/michaelwzhu/Chinese-LlaMA2-7B)进行指令微调和多轮对话微调，以适应各种应用场景和多轮对话交互。

注意，为了遵循相应的许可，我们将不会发布完整的模型权重，只发布LoRA权重，其与Meta的LlaMA2权重合并即可形成Chinese-LlaMA2模型。

同时，我们将会围绕Chinese-LlaMA2打造各种垂直领域模型：
- ⏳[Chinese-LlaMA2-chatmed](https://huggingface.co/michaelwzhu/Chinese-LlaMA2-7B-chatmed): Chinese-LlaMA2医学领域大模型，支持多轮在线问诊；
- ⏳[Chinese-LlaMA2-tcm](https://huggingface.co/michaelwzhu/Chinese-LlaMA2-7B-tcm): Chinese-LlaMA2中医药大模型，专注于中医药细分领域，赋能中医药传承


## 更新