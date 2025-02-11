# LibreChat YAML Configuration Files

This repository provides YAML configuration files for [LibreChat](https://www.librechat.ai/), allowing for flexible and efficient configuration management.

## Key Differences

- **`librechat-env.yaml`**: Utilizes `.env` variables, eliminating the need to manually provide the API Key.
- **`librechat-user-provided.yaml`**: Allows users to manually input their API key via the LibreChat front end.

## Usage Guide

### Basic Usage

1. Choose either `librechat-env.yaml` or `librechat-user-provided.yaml`.
2. Copy the RAW URL of the selected file.
3. Locate and edit your `.env` file in the project folder.
4. Uncomment the following section and replace `<RAW_URL_GOES_HERE>` with the RAW URL:

    ```plaintext
    #===============#
    # Configuration #
    #===============#
    # Use an absolute path, a relative path, or a URL

    CONFIG_PATH=<RAW_URL_GOES_HERE>
    ```

### Advanced Usage

1. Create a file named `librechat.yaml` at the project root (if it doesn’t already exist).
2. Copy and paste the content of one of the YAML configuration files.
3. Modify the configuration as needed.

## RAW URLs

- **`librechat-env.yaml`**:
  ```plaintext
  https://raw.githubusercontent.com/febryanvaldo/LibreChat/refs/heads/main/librechat-env.yaml
  ```

- **`librechat-user-provided.yaml`**:
  ```plaintext
  https://raw.githubusercontent.com/febryanvaldo/LibreChat/refs/heads/main/librechat-user-provided.yaml
  ```

## Validation and Formatting

To validate and format your YAML configuration, you can use the following tools:

- [Elmah YAML Formatter](https://elmah.io/tools/yaml-formatter/)
- [JSON Formatter YAML Validator](https://jsonformatter.org/yaml-validator)

## Additional Resources

For more detailed information regarding LibreChat configuration, refer to the [LibreChat Custom Config Documentation](https://www.librechat.ai/docs/configuration).

---

Feel free to contribute to this repository by submitting issues or pull requests. Your feedback and contributions are greatly appreciated!
