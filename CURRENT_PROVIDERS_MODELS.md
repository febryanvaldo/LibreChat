```plaintext 
==================================================
2025-04-02 10:31:52 GMT+7
==================================================
🤖 Anthropic   : 7 models (no change)
🤖 Google      : 17 models (+2 models)
🤖 OpenAI      : 32 models (no change)
🤖 Cohere      : 10 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 41 models (no change)
🤖 Perplexity  : 6 models (no change)
🤖 xAI         : 5 models (no change)
🤖 Cerebras    : 2 models (no change)
🤖 Groq        : 20 models (no change)
🤖 Sambanova   : 20 models (no change)
🤖 Chutes      : 37 models (+1 model)
🤖 DeepInfra   : 75 models (no change)
🤖 Fireworks   : 25 models (no change)
🤖 FriendliAI  : 4 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 8 models (no change)
🤖 Nebius      : 66 models (no change)
🤖 Novita AI   : 41 models (no change)
🤖 ShuttleAI   : 133 models (no change)
🤖 Targon      : 11 models (no change)
🤖 Together AI : 51 models (no change)
🤖 APIpie      : 328 models (-5 models)
🤖 NanoGPT     : 200 models (no change)
🤖 OpenRouter  : 293 models (no change)
🤖 Requesty    : 191 models (no change)
🤖 UnifyAI     : 162 models (no change)
==================================================
2025-04-02 10:31:52 GMT+7
==================================================

==================================================
2025-04-03 11:07:13 GMT+7
==================================================
🤖 Anthropic   : 7 models (no change)
🤖 Google      : 18 models (+1 model)
🤖 OpenAI      : 32 models (no change)
🤖 Cohere      : 10 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 41 models (no change)
🤖 Perplexity  : 6 models (no change)
🤖 xAI         : 5 models (no change)
🤖 Cerebras    : 2 models (no change)
🤖 Groq        : 20 models (no change)
🤖 Sambanova   : 20 models (no change)
🤖 Chutes      : 37 models (no change)
🤖 DeepInfra   : 75 models (no change)
🤖 Fireworks   : 28 models (+3 models)
🤖 FriendliAI  : 4 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 8 models (no change)
🤖 Nebius      : 66 models (no change)
🤖 Novita AI   : 41 models (no change)
🤖 ShuttleAI   : 133 models (no change)
🤖 Targon      : 11 models (no change)
🤖 Together AI : 51 models (no change)
🤖 APIpie      : 329 models (+1 model)
🤖 NanoGPT     : 200 models (no change)
🤖 OpenRouter  : 291 models (-2 models)
🤖 Requesty    : 191 models (no change)
🤖 UnifyAI     : 162 models (no change)
==================================================
2025-04-03 11:07:13 GMT+7
==================================================

==================================================
2025-04-04 10:37:50 GMT+7
==================================================
🤖 Anthropic   : 7 models (no change)
🤖 Google      : 18 models (no change)
🤖 OpenAI      : 32 models (no change)
🤖 Cohere      : 10 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 41 models (no change)
🤖 Perplexity  : 6 models (no change)
🤖 xAI         : 5 models (no change)
🤖 Cerebras    : 2 models (no change)
🤖 Groq        : 20 models (no change)
🤖 Sambanova   : 20 models (no change)
🤖 Chutes      : 37 models (no change)
🤖 DeepInfra   : 75 models (no change)
🤖 Fireworks   : 29 models (+1 model)
🤖 FriendliAI  : 4 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 8 models (no change)
🤖 Nebius      : 66 models (no change)
🤖 Novita AI   : 41 models (no change)
🤖 ShuttleAI   : 133 models (no change)
🤖 Targon      : 11 models (no change)
🤖 Together AI : 51 models (no change)
🤖 APIpie      : 329 models (no change)
🤖 NanoGPT     : 201 models (+1 model)
🤖 OpenRouter  : 289 models (-2 models)
🤖 Requesty    : 191 models (no change)
🤖 UnifyAI     : 162 models (no change)
==================================================
2025-04-04 10:37:50 GMT+7
==================================================
```

### OpenRouter Web Search Models
I added 3 models that use capabilities of OpenRouter Web Search feature. OpenRouter use Exa.ai for the Web Search.

The models are;
- `anthropic/claude-3.7-sonnet:online` base model of **Claude 3.7 Sonnet**
- `google/gemini-2.0-flash-001:online` base model of **Gemini Flash 2.0**
- `openai/chatgpt-4o-latest:online` base model of **GPT-4o**

### NanoGPT Web Search Models 
Like OpenRouter above, i also added 6 models that can utilize the NanoGPT Web Search feature. NanoGPT uses Linkup.so for the Web Search. The `:online` is the standard one, while `:online/linkup-deep` is the deep search one.

The models are;
- `chatgpt-4o-latest:online` base model of **GPT-4o**
- `chatgpt-4o-latest:online/linkup-deep` base model of **GPT-4o**
- `claude-3-7-sonnet-20250219:online` base model of **Claude 3.7 Sonnet**
- `claude-3-7-sonnet-20250219:online/linkup-deep` base model of **Claude 3.7 Sonnet**
- `gemini-2.0-flash-001:online` base model of **Gemini Flash 2.0**
- `gemini-2.0-flash-001:online/linkup-deep` base model of **Gemini Flash 2.0**