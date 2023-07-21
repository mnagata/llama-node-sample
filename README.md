# llama-node-sample

### 実行例
```
./node_modules/.bin/ts-node src/llama.ts "What is the highest mountain in Japan?"
llama.cpp: loading model from /Users/mnagata/git/llama-node-sample/models/llama-2-7b-chat.ggmlv3.q8_0.bin
llama_model_load_internal: format     = ggjt v3 (latest)
llama_model_load_internal: n_vocab    = 32000
llama_model_load_internal: n_ctx      = 1024
llama_model_load_internal: n_embd     = 4096
llama_model_load_internal: n_mult     = 256
llama_model_load_internal: n_head     = 32
llama_model_load_internal: n_layer    = 32
llama_model_load_internal: n_rot      = 128
llama_model_load_internal: ftype      = 7 (mostly Q8_0)
llama_model_load_internal: n_ff       = 11008
llama_model_load_internal: n_parts    = 1
llama_model_load_internal: model size = 7B
llama_model_load_internal: ggml ctx size =    0.07 MB
llama_model_load_internal: mem required  = 8620.71 MB (+ 2052.00 MB per state)
.
llama_init_from_file: kv self size  = 1024.00 MB
[Fri, 21 Jul 2023 07:52:06 +0000 - INFO - llama_node_cpp::context] - AVX = 1 | AVX2 = 1 | AVX512 = 0 | AVX512_VBMI = 0 | AVX512_VNNI = 0 | FMA = 1 | NEON = 0 | ARM_FMA = 0 | F16C = 1 | FP16_VA = 0 | WASM_SIMD = 0 | BLAS = 1 | SSE3 = 1 | VSX = 0 | 
[Fri, 21 Jul 2023 07:52:06 +0000 - INFO - llama_node_cpp::llama] - tokenized_stop_prompt: Some([13])
 The highest mountain in Japan is Mount Fuji, which is located on Honshu Island and stands at an elevation of 3,776 meters (12,388 feet) above sea level. It is considered one of Japan's "Three Holy Mountains" and is a popular destination for hiking and climbing.

<end>
```
