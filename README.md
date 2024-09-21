# reverse_turing
a simple bash script to run a reverse turing test on a LLM

Reference: https://www.youtube.com/watch?v=MxTWLm9vT_o

Tested models:                acc

   Llama 3.1 8B Q4_K_M   4/4  1.0
   
   glm4 9B Q6_K          4/4  1.0
   
   openchat 7B 0106 Q8_0 4/4  1.0
   
   solar 10.7B Q6_K      4/4  1.0

   solar pro preview IQ4_XS 4/4 1.0
   
   phi 3.5 3.8B 8k Q6_K  2/4  0.5
   
   Mistral Nemo 12B Q4_K_M 1/4 0.25
   
   gemma 2 9B Q6_K       1/4  0.25
   
   internlm 7B Q6_K      1/4  0.25
   
   gemma 2 27B IQ4_XS    1/4  0.25
   
   qwen 2 7B Q6_K        0/4  0.00
   
   openchat 3.6 8B Q8_0  0/4  0.00
   
   mistral 7B v0.3       0/4  0.00
   
   phi 3 medium 14B      does not follow instructions
   
   gemma 2 2B Q8_0       does not follow instructions
