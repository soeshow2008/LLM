https://qwen.readthedocs.io/zh-cn/latest/run_locally/llama.cpp.html#
https://hf-mirror.com/Qwen/Qwen2-0.5B-Instruct-GGUF

git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp
make

huggingface-cli download Qwen/Qwen2-0.5B-Instruct-GGUF qwen2-0_5b-instruct-q5_k_m.gguf --local-dir . --local-dir-use-symlinks False

./llama-server -m qwen2-0_5b-instruct-q5_k_m.gguf -ngl 24 -fa


