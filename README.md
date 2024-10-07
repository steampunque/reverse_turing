# reverse_turing
a simple bash script to run a reverse turing test on a LLM

Reference: https://www.youtube.com/watch?v=MxTWLm9vT_o

Tested models:        |  score  | acc
----------------------|----------|------
solar 10.7B Q6_K      |  4/4  | 1.0
openchat 7B 0106 Q6_K |  3/4  | 0.75
gemma 2 2B Q8_0       | 3/4 | 0.75
qwen 2.5 instruct 7B Q4_K_M | 3/4  | 0.75 
internlm 7B IQ4_XS    |  3/4  | 0.75
Llama 3.1 8B IQ4_XS   |  2/4  | 0.5
phi 3.5 3.8B 8k Q6_K  | 2/4  | 0.5
Llama 3.2 3B instruct Q6_K   | 2/4 | 0.5
glm4 9B IQ4_XS        |  1/4  | 0.125
openchat 3.6 8B Q6_K  |  1/4  | 0.125
mistral 7B v0.3 Q6_K  |  1/4  | 0.125
gemma 2 9B Q4_K_M  |  1/4  | 0.125
qwen 2 7B IQ4_XS      |  0/4  | 0.0
solar pro preview 22B IQ4_XS |  | 
Mistral Nemo 12B Q4_K_M |  | 
gemma 2 27B IQ4_XS    |    | 
qwen 2.5 instruct 32B IQ4_XS |  | 
Qwen 2.5 instruct 14B IQ4_XS |  |
phi 3 medium 14B      |  |
