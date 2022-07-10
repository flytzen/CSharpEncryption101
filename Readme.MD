# C# Encryption 101
> the very basics you need to avoid doing encryption wrong

C# has excellent encryption algorithms, but they are implemented in a way that make them really hard to use correctly.  
When doing [security reviews](https://neworbit.co.uk/azure) I too often come across basic mistakes when encrypting data.

This 15-minute talk covers the most common mistakes. It does not try to teach you how it all works or how to choose different algorithms or settings. Instead, it tells you what to do when you just want to encrypt some data with a known key. No ifs, no buts.

The talk is delivered as a [Notebook](CSharpEncryption101.ipynb), which renders pretty well directly on GitHub, so give that a go. If you want to run the examples, just clone the repo and install the [.NET Interactive Notebooks extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)
