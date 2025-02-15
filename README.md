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
  - [Update Policy](#update-policy)
  - [Validation and Formatting](#validation-and-formatting)
  - [Additional Resources](#additional-resources)

---

## Key Differences

- **`librechat-env.yaml`** - Uses `.env` variables with the API key hardcoded in the `.env` file, making it suitable for single-user usage.
- **`librechat-user-provided.yaml`** – Allows users to manually input the API key via the LibreChat front end, suitable for multi-user environments.

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

5. **Configure your environment keys (For `librechat-env.yaml` only)**
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
COHERE_KEY=Your_API_Key_Here
DEEPSEEK_KEY=Your_API_Key_Here
MISTRALAI_KEY=Your_API_Key_Here
PERPLEXITY_KEY=Your_API_Key_Here
XAI_KEY=Your_API_Key_Here
GROQ_KEY=Your_API_Key_Here
SAMBANOVA_KEY=Your_API_Key_Here
FIREWORKSAI_KEY=Your_API_Key_Here
HYPERBOLIC_KEY=Your_API_Key_Here
KLUSTERAI_KEY=Your_API_Key_Here
NEBIUS_KEY=Your_API_Key_Here
SHUTTLEAI_KEY=Your_API_Key_Here
TOGETHERAI_KEY=Your_API_Key_Here
APIPIE_KEY=Your_API_Key_Here
NANOGPT_KEY=Your_API_Key_Here
OPENROUTER_KEY=Your_API_Key_Here
REQUESTY_KEY=Your_API_Key_Here
```

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