```plaintext
==================================================
2025-07-01 10:16:01 GMT+7
==================================================
🤖 Anthropic   : 6 models (no change)
🤖 Google      : 22 models (no change)
🤖 OpenAI      : 42 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 45 models (no change)
🤖 Perplexity  : 6 models (no change)
🤖 xAI         : 7 models (no change)
🤖 Cerebras    : 4 models (no change)
🤖 Groq        : 19 models (no change)
🤖 Sambanova   : 9 models (no change)
🤖 Chutes      : 34 models (-10 models)
🤖 DeepInfra   : 98 models (+1 model)
🤖 Fireworks   : 24 models (-1 model)
🤖 FriendliAI  : 3 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 13 models (no change)
🤖 Nebius      : 46 models (no change)
🤖 Novita AI   : 51 models (+4 models)
🤖 ShuttleAI   : 21 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 8 models (no change)
🤖 Together AI : 58 models (no change)
🤖 APIpie      : 530 models (-1 model)
🤖 NanoGPT     : 342 models (no change)
🤖 OpenRouter  : 322 models (+1 model)
🤖 Requesty    : 267 models (no change)
🤖 UnifyAI     : 173 models (-1 model)
==================================================
2025-07-01 10:16:01 GMT+7
==================================================

==================================================
2025-07-02 09:42:06 GMT+7
==================================================
🤖 Anthropic   : 6 models (no change)
🤖 Google      : 22 models (no change)
🤖 OpenAI      : 42 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 45 models (no change)
🤖 Perplexity  : 6 models (no change)
🤖 xAI         : 7 models (no change)
🤖 Cerebras    : 4 models (no change)
🤖 Groq        : 19 models (no change)
🤖 Sambanova   : 9 models (no change)
🤖 Chutes      : 51 models (+17 models)
🤖 DeepInfra   : 98 models (no change)
🤖 Fireworks   : 24 models (no change)
🤖 FriendliAI  : 3 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 14 models (+1 model)
🤖 Nebius      : 46 models (no change)
🤖 Novita AI   : 51 models (no change)
🤖 ShuttleAI   : 21 models (no change)
🤖 Synthetic   : 21 models (no change)
🤖 Targon      : 3 models (-5 models)
🤖 Together AI : 59 models (+1 model)
🤖 APIpie      : 533 models (+3 models)
🤖 NanoGPT     : 342 models (no change)
🤖 OpenRouter  : 321 models (-1 model)
🤖 Requesty    : 256 models (-11 models)
🤖 UnifyAI     : 173 models (no change)
==================================================
2025-07-02 09:42:06 GMT+7
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