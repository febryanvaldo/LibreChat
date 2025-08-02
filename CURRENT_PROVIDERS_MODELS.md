```plaintext
==================================================
2025-08-02 11:27:03 GMT+7
==================================================
🤖 Anthropic   : 6 models (no change)
🤖 Google      : 21 models (no change)
🤖 OpenAI      : 44 models (no change)
🤖 Cohere      : 11 models (no change)
🤖 DeepSeek    : 2 models (no change)
🤖 Mistral AI  : 55 models (no change)
🤖 Perplexity  : 5 models (no change)
🤖 xAI         : 8 models (no change)
🤖 Cerebras    : 8 models (+2 models)
🤖 Groq        : 18 models (no change)
🤖 Sambanova   : 10 models (no change)
🤖 Chutes      : 65 models (+1 model)
🤖 DeepInfra   : 107 models (no change)
🤖 Fireworks   : 27 models (+3 models)
🤖 FriendliAI  : 9 models (no change)
🤖 Hyperbolic  : 20 models (no change)
🤖 KlusterAI   : 1 model (no change)
🤖 Nebius      : 47 models (+1 model)
🤖 Novita AI   : 52 models (no change)
🤖 ShuttleAI   : 21 models (no change)
🤖 Synthetic   : 25 models (no change)
🤖 Targon      : 9 models (no change)
🤖 Together AI : 64 models (+3 models)
🤖 APIpie      : 557 models (+1 model)
🤖 NanoGPT     : 389 models (+2 models)
🤖 OpenRouter  : 321 models (-2 models)
🤖 Requesty    : 374 models (+31 models)
🤖 UnifyAI     : 161 models (no change)
==================================================
2025-08-02 11:27:03 GMT+7
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