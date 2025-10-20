```plaintext
==================================================
2025-10-13 09:10:06 GMT+7
==================================================
🤖 Anthropic   : 8 models (no change)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 46 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 9 models (no change)
🤖 Groq        : 17 models (-1 model)
🤖 Sambanova   : 13 models (no change)
🤖 Baseten     : 8 models (no change)
🤖 DeepInfra   : 122 models (no change)
🤖 Fireworks   : 34 models (no change)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 115 models (+3 models)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 65 models (-3 models)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 72 models (no change)
🤖 302.AI      : 492 models (no change)
🤖 APIpie      : 611 models (-2 models)
🤖 NanoGPT     : 454 models (+2 models)
🤖 OpenRouter  : 334 models (+7 models)
🤖 Requesty    : 489 models (no change)
🤖 UnifyAI     : 160 models (no change)
==================================================
2025-10-13 09:10:06 GMT+7
==================================================

==================================================
2025-10-16 09:14:56 GMT+7
==================================================
🤖 Anthropic   : 9 models (+1 model)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 48 models (+2 models)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 8 models (-1 model)
🤖 Groq        : 17 models (no change)
🤖 Sambanova   : 13 models (no change)
🤖 Baseten     : 9 models (+1 model)
🤖 DeepInfra   : 130 models (+8 models)
🤖 Fireworks   : 34 models (no change)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 115 models (no change)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 65 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 69 models (-3 models)
🤖 302.AI      : 503 models (+11 models)
🤖 APIpie      : 620 models (+9 models)
🤖 NanoGPT     : 439 models (-15 models)
🤖 OpenRouter  : 339 models (+5 models)
🤖 Requesty    : 352 models (-137 models)
🤖 UnifyAI     : 160 models (no change)
==================================================
2025-10-16 09:14:56 GMT+7
==================================================

==================================================
2025-10-20 08:51:06 GMT+7
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
🤖 DeepInfra   : 132 models (+2 models)
🤖 Fireworks   : 34 models (no change)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 115 models (no change)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 65 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 66 models (-3 models)
🤖 302.AI      : 503 models (no change)
🤖 APIpie      : 629 models (+9 models)
🤖 NanoGPT     : 439 models (no change)
🤖 OpenRouter  : 343 models (+4 models)
🤖 Requesty    : 357 models (+5 models)
🤖 UnifyAI     : 160 models (no change)
==================================================
2025-10-20 08:51:06 GMT+7
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