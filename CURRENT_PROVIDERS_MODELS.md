```plaintext
==================================================
2025-10-02 08:20:01 GMT+7
==================================================
🤖 Anthropic   : 8 models (+1 model)
🤖 Google      : 26 models (+5 models)
🤖 OpenAI      : 54 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (-2 models)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 9 models (no change)
🤖 Groq        : 19 models (no change)
🤖 Sambanova   : 13 models (+1 model)
🤖 Baseten     : 11 models (no change)
🤖 DeepInfra   : 121 models (+4 models)
🤖 Fireworks   : 33 models (-1 model)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 114 models (+3 models)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 70 models (+6 models)
🤖 Synthetic   : 21 models (+1 model)
🤖 Targon      : 9 models (no change)
🤖 Together AI : 63 models (-1 model)
🤖 302.AI      : 489 models (+25 models)
🤖 APIpie      : 608 models (+27 models)
🤖 NanoGPT     : 459 models (+13 models)
🤖 OpenRouter  : 334 models (+7 models)
🤖 Requesty    : 487 models (+13 models)
🤖 UnifyAI     : 161 models (+2 models)
==================================================
2025-10-02 08:20:01 GMT+7
==================================================

==================================================
2025-10-03 10:37:45 GMT+7
==================================================
🤖 Anthropic   : 8 models (no change)
🤖 Google      : 26 models (no change)
🤖 OpenAI      : 54 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 58 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 9 models (no change)
🤖 Cerebras    : 9 models (no change)
🤖 Groq        : 19 models (no change)
🤖 Sambanova   : 13 models (no change)
🤖 Baseten     : 11 models (no change)
🤖 DeepInfra   : 121 models (no change)
🤖 Fireworks   : 33 models (no change)
🤖 FriendliAI  : 10 models (no change)
🤖 Hugging Face: 114 models (no change)
🤖 Hyperbolic  : 26 models (no change)
🤖 Nebius      : 41 models (no change)
🤖 Novita AI   : 70 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 9 models (no change)
🤖 Together AI : 65 models (+2 models)
🤖 302.AI      : 489 models (no change)
🤖 APIpie      : 608 models (no change)
🤖 NanoGPT     : 458 models (-1 model)
🤖 OpenRouter  : 333 models (-1 model)
🤖 Requesty    : 487 models (no change)
🤖 UnifyAI     : 161 models (no change)
==================================================
2025-10-03 10:37:45 GMT+7
==================================================
```

### OpenRouter Web Search Models
I added 3 models that use capabilities of OpenRouter Web Search feature. OpenRouter use Exa.ai for the Web Search.

The models are;
- `anthropic/claude-sonnet-4:online` based on **Claude 4 Sonnet**
- `google/gemini-2.5-flash:online` based on **Gemini 2.5 Flash Stable**
- `openai/gpt-4.1:online` based on **OpenAI's GPT-4.1**

### NanoGPT Web Search Models 
Like OpenRouter above, i also added 6 models that can utilize the NanoGPT Web Search feature. NanoGPT uses Linkup.so for the Web Search. The `:online` is the **standard** one, while `:online/linkup-deep` is the **deep search** one.

The models are;
- `claude-sonnet-4-20250514:online` based on **Claude 4 Sonnet**
- `claude-sonnet-4-20250514:online/linkup-deep` based on **Claude 4 Sonnet**
- `gemini-2.5-flash:online` based on **Gemini 2.5 Flash Stable**
- `gemini-2.5-flash:online/linkup-deep` based on **Gemini 2.5 Flash Stable**
- `openai/gpt-4.1:online` based on **OpenAI's GPT-4.1**
- `openai/gpt-4.1:online/linkup-deep` based on **OpenAI's GPT-4.1**