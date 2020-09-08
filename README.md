# Strathweb.Samples.BlazorCSharpInteractive

Demo code for a blog post [Building a C# Interactive shell in a browser with Blazor (WebAssembly) and Roslyn](https://www.strathweb.com/2019/06/building-a-c-interactive-shell-in-a-browser-with-blazor-webassembly-and-roslyn/)

The code reflecting the article is available on the [article branch](https://github.com/filipw/Strathweb.Samples.BlazorCSharpInteractive/tree/article).

The master branch contains additional features and improvements not mentioned in the article.

### Warning

The code looks now a little different from the article because it has been updated to Blazor WASM 5.0 Preview 8.
Due to https://github.com/dotnet/runtime/pull/41761 the solution currently doesn't work (requires changes bringing back SHA functions).