# dotstrings

This is a Python toolkit for interacting with the localization files for iOS and macOS.

### Examples

**Read in a .strings file and print the entries:**
```python
import dotstrings

entries = dotstrings.load("/path/to/file.strings")

for entry in entries:
    print("Key: " + entry.key)
    print("Value: " + entry.value)
    print("Comment: " + entry.comment)
```

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.