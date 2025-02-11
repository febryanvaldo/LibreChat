# LibreChat YAML Configuration Files

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository provides YAML configuration files for [LibreChat](https://www.librechat.ai/), enabling flexible and efficient configuration management.

---

## Table of Contents

- [LibreChat YAML Configuration Files](#librechat-yaml-configuration-files)
  - [Table of Contents](#table-of-contents)
  - [Key Differences](#key-differences)
  - [Usage Guide](#usage-guide)
    - [Basic Usage](#basic-usage)
    - [Advanced Usage](#advanced-usage)
  - [RAW URLs](#raw-urls)
  - [.ENV Configuration](#env-configuration)
  - [Current Providers \& Total Models](#current-providers--total-models)
  - [Update Policy](#update-policy)
  - [Validation and Formatting](#validation-and-formatting)
  - [Additional Resources](#additional-resources)

---

## Key Differences

- **`librechat-env.yaml`** – Uses `.env` variables so you don’t need to manually provide the API key.
- **`librechat-user-provided.yaml`** – Allows you to manually input your API key via the LibreChat front end.

---

## Usage Guide

### Basic Usage

1. **Select a configuration file**  
   Choose either `librechat-env.yaml` or `librechat-user-provided.yaml`.

2. **Obtain the RAW URL**  
   Copy the RAW URL of the chosen file (see [RAW URLs](#raw-urls)).

3. **Edit your `.env` file**  
   Locate your project’s `.env` file and open it for editing.

4. **Update the CONFIG_PATH**  
   Uncomment the `CONFIG_PATH` line and replace `<RAW_URL_GOES_HERE>` with the copied URL:

   ```plaintext
   #===============#
   # Configuration #
   #===============#
   # Use an absolute path, a relative path, or a URL

   CONFIG_PATH=<RAW_URL_GOES_HERE>
   ```

5. **(For librechat-env.yaml only) Configure your environment keys**  
   Replace `<ENV_GOES_HERE>` with the provided .env configuration values:

   ```plaintext
   #===================================#
   # Known Endpoints - librechat.yaml  #
   #===================================#
   # See: https://www.librechat.ai/docs/configurationlibrechat_yamlai_endpoints

   <ENV_GOES_HERE>
   ```

### Advanced Usage

1. Create a file named `librechat.yaml` at the project root (if it doesn’t exist already).
2. Copy and paste the entire content of one of the YAML configuration files into it.
3. Modify the configuration as needed.

---

## RAW URLs

- **`librechat-env.yaml`**  
  ```plaintext
  https://raw.githubusercontent.com/febryanvaldo/LibreChat/refs/heads/main/librechat-env.yaml
  ```

- **`librechat-user-provided.yaml`**  
  ```plaintext
  https://raw.githubusercontent.com/febryanvaldo/LibreChat/refs/heads/main/librechat-user-provided.yaml
  ```

---

## .ENV Configuration

```plaintext
COHERE_KEY=YourAPIKey
DEEPSEEK_KEY=YourAPIKey
MISTRALAI_KEY=YourAPIKey
PERPLEXITY_KEY=YourAPIKey
XAI_KEY=YourAPIKey
GROQ_KEY=YourAPIKey
SAMBANOVA_KEY=YourAPIKey
FIREWORKSAI_KEY=YourAPIKey
NEBIUS_KEY=YourAPIKey
SHUTTLEAI_KEY=YourAPIKey
TOGETHERAI_KEY=YourAPIKey
APIPIE_KEY=YourAPIKey
NANOGPT_KEY=YourAPIKey
OPENROUTER_KEY=YourAPIKey
REQUESTY_KEY=YourAPIKey
UNIFY_KEY=YourAPIKey
```

---

## Current Providers & Total Models

```plaintext
==================================================
2025-02-10 10:44:38
==================================================
📝 Anthropic   : 6 models (no change)
📝 Google      : 26 models (no change)
📝 OpenAI      : 19 models (no change)
📝 Cohere      : 8 models (no change)
📝 DeepSeek    : 2 models (no change)
📝 Mistral AI  : 35 models (no change)
📝 Perplexity  : 4 models (no change)
📝 xAI         : 4 models (no change)
📝 Groq        : 14 models (no change)
📝 SambaNova   : 14 models (no change)
📝 Fireworks   : 26 models (no change)
📝 Nebius      : 56 models (no change)
📝 ShuttleAI   : 138 models (-1 model)
📝 Together AI : 49 models (no change)
📝 APIpie      : 273 models (-1 model)
📝 NanoGPT     : 142 models (no change)
📝 OpenRouter  : 228 models (no change)
📝 Requesty    : 160 models (+4 models)
📝 UnifyAI     : 158 models (no change)
==================================================
2025-02-11 10:11:47
==================================================
📝 Anthropic   : 6 models (no change)
📝 Google      : 26 models (no change)
📝 OpenAI      : 19 models (no change)
📝 Cohere      : 8 models (no change)
📝 DeepSeek    : 2 models (no change)
📝 Mistral AI  : 37 models (+2 models)
📝 Perplexity  : 4 models (no change)
📝 xAI         : 4 models (no change)
📝 Groq        : 16 models (+2 models)
📝 SambaNova   : 14 models (no change)
📝 Fireworks   : 26 models (no change)
📝 Nebius      : 56 models (no change)
📝 ShuttleAI   : 138 models (no change)
📝 Together AI : 49 models (no change)
📝 APIpie      : 272 models (-1 model)
📝 NanoGPT     : 141 models (-1 model)
📝 OpenRouter  : 228 models (no change)
📝 Requesty    : 157 models (-3 models)
📝 UnifyAI     : 160 models (+2 models)
```

*Note: The above data reflects the model count at the indicated timestamps for the last 2 days*

---

## Update Policy

I strive to update the configuration on a daily basis. Stay tuned for new changes and improvements.

---

## Validation and Formatting

To validate and format your YAML configuration files, you can use these online tools:

- [Elmah YAML Formatter](https://elmah.io/tools/yaml-formatter/)
- [JSON Formatter YAML Validator](https://jsonformatter.org/yaml-validator)

---

## Additional Resources

For detailed documentation on LibreChat configuration, please see the [LibreChat Custom Config Documentation](https://www.librechat.ai/docs/configuration).

---