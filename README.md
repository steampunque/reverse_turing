# reverse_turing
a simple bash script to run a reverse turing test on a LLM

Reference: https://www.youtube.com/watch?v=MxTWLm9vT_o

Tested models:        |  score  | acc
----------------------|----------|------
Llama 3.1 8B instruct Q6_K   | 4/4 | 1.0
phi 3.5 3.8B 8k instruct Q6_K | 4/4 | 1.0
phi 3 medium 128k instruct 14B IQ4_XS  | 4/4 | 1.0
solar 10.7B instruct Q6_K    | 4/4 | 1.0
solar pro preview instruct 22B IQ4_XS | 4/4 | 1.0
Qwen 2.5 instruct 32B IQ4_XS | 4/4  | 1.0
gemma 2 2B it Q8_0       | 3/4 | 0.75
glm4 9B chat IQ4_XS        | 3/4 | 0.75
mistral 7B instruct v0.3 Q6_K  |  3/4  | 0.75
internlm 7B chat Q6_K    |  2/4  | 0.5
Llama 3.2 3B instruct Q6_K | 2/4 | 0.5
Ministral 8B Instruct 2410 Q6_K | 2/4 | 0.5
Mistral Small 22B Instruct 2409 Q6_K | 2/4 | 0.5
openchat 7B 0106 Q8_0 | 2/4 | 0.5
phi 3 medium 4k instruct 14B IQ4_XS  | 2/4 | 0.5
gemma 2 9B it Q6_K     | 1/4 | 0.25
gemma 2 27B it IQ4_XS    | 1/4 | 0.25
granite 3.0 8B instruct Q6_K   | 1/4      | 0.25
Mistral Nemo 12B Q4_K_M | 1/4 | 0.25
openchat 3.6 8B Q8_0  | 1/4 | 0.25
phi 3.5 3.8B 128k Q6_K | 1/4 | 0.25
qwen 2 7B Q6_K               | 1/4 | 0.25
qwen 2.5 instruct 7B Q6_K | 1/4 | 0.25
Qwen 2.5 instruct 14B IQ4_XS | 1/4 | 0.25
granite 3.0 2B instruct Q6_K   | 0/4      | 0.0
