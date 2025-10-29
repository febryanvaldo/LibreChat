```plaintext
==================================================
2025-10-24 10:40:37 GMT+7
==================================================
🤖 Anthropic   : 9 models (no change)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 48 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 8 models (no change)
🤖 Groq        : 17 models (no change)
🤖 Sambanova   : 13 models (no change)
🤖 Baseten     : 9 models (no change)
🤖 DeepInfra   : 134 models (no change)
🤖 Fireworks   : 30 models (-5 models)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 116 models (+1 model)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 68 models (-1 model)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 67 models (+1 model)
🤖 302.AI      : 500 models (-4 models)
🤖 APIpie      : 628 models (-1 model)
🤖 NanoGPT     : 438 models (-1 model)
🤖 OpenRouter  : 350 models (+9 models)
🤖 Requesty    : 376 models (+11 models)
🤖 UnifyAI     : 163 models (no change)
==================================================
2025-10-24 10:40:37 GMT+7
==================================================

==================================================
2025-10-26 10:55:18 GMT+7
==================================================
🤖 Anthropic   : 9 models (no change)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 48 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 8 models (no change)
🤖 Groq        : 17 models (no change)
🤖 Sambanova   : 13 models (no change)
🤖 Baseten     : 9 models (no change)
🤖 DeepInfra   : 134 models (no change)
🤖 Fireworks   : 34 models (no change)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 116 models (+1 model)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 69 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 67 models (no change)
🤖 302.AI      : 502 models (+2 models)
🤖 APIpie      : 632 models (+3 models)
🤖 NanoGPT     : 439 models (+1 model)
🤖 OpenRouter  : 350 models (-1 model)
🤖 Requesty    : 376 models (no change)
🤖 UnifyAI     : 163 models (no change)
==================================================
2025-10-26 10:55:18 GMT+7
==================================================

==================================================
2025-10-29 10:10:04 GMT+7
==================================================
🤖 Anthropic   : 7 models (-2 models)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 48 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 8 models (no change)
🤖 Groq        : 17 models (no change)
🤖 Sambanova   : 14 models (+1 model)
🤖 Baseten     : 9 models (no change)
🤖 DeepInfra   : 76 models (-58 models)
🤖 Fireworks   : 35 models (+1 model)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 116 models (no change)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 42 models (+1 model)
🤖 Novita AI   : 70 models (+1 model)
🤖 Synthetic   : 22 models (+1 model)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 67 models (no change)
🤖 302.AI      : 505 models (+3 models)
🤖 APIpie      : 629 models (-3 models)
🤖 NanoGPT     : 442 models (+3 models)
🤖 OpenRouter  : 348 models (-2 models)
🤖 Requesty    : 376 models (no change)
🤖 UnifyAI     : 161 models (-2 models)
==================================================
2025-10-29 10:10:04 GMT+7
==================================================
```

### OpenRouter Web Search Models

I added 3 models that use capabilities of OpenRouter Web Search feature. OpenRouter use Exa.ai for the Web Search.

The models are;

- `anthropic/claude-sonnet-4.5:online` based on **Claude 4.5 Sonnet**
- `google/gemini-2.5-flash:online` based on **Gemini 2.5 Flash Stable**
- `openai/gpt-4.1:online` based on **OpenAI's GPT-4.1**

### NanoGPT Web Search Models

Like OpenRouter above, i also added 6 models that can utilize the NanoGPT Web Search feature. NanoGPT uses Linkup.so for the Web Search. The `:online` is the **standard** one, while `:online/linkup-deep` is the **deep search** one.

The models are;

- `claude-sonnet-4-5-20250929:online` based on **Claude 4.5 Sonnet**
- `claude-sonnet-4-5-20250929:online/linkup-deep` based on **Claude 4.5 Sonnet**
- `gemini-2.5-flash:online` based on **Gemini 2.5 Flash Stable**
- `gemini-2.5-flash:online/linkup-deep` based on **Gemini 2.5 Flash Stable**
- `openai/gpt-4.1:online` based on **OpenAI's GPT-4.1**
- `openai/gpt-4.1:online/linkup-deep` based on **OpenAI's GPT-4.1**
