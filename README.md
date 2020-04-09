# Understanding-text-editor-themes

Most modern IDEs include a feature called _Synthax highlighting_. We'll try to understand how such a feature is made possible across different programming languages.

## Synthax highlighting

```
Syntax highlighting is a feature of text editors that are used for programming, scripting, or markup languages, such as HTML. The feature displays text, especially source code, in different colors and fonts according to the category of terms. This feature facilitates writing in a structured language such as a programming language or a markup language as both structures and syntax errors are visually distinct. Highlighting does not affect the meaning of the text itself; it is intended only for human readers.
```

There are different ways this can be done. For instance, VS Code [explains how](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide) it uses [TextMate](https://macromates.com/manual/en/language_grammars) grammars to break text into a list of tokens.
These **tokens** are then assigned to different colors.

## Semantic highlighting

_Semantic Highlighting_ is an improvement made on top of _Synthax highlighting_, in an effort to not only make code more readable but also more understandable as exlpained in [this excellent post](https://zwabel.wordpress.com/2009/01/08/c-ide-evolution-from-syntax-highlighting-to-semantic-highlighting/).

## Understanding VS Code

In VS Code, themes are either stored inside of a theme are can be edited in your `settings.json` file, where you can customize _Workbench colors_(UI elements of VS) and the actual _Synthax colors_.
Microsoft gives us a the full breakdown of available customizations on [this page](https://code.visualstudio.com/api/references/theme-color).

## How to generate a color theme
This great [post](https://css-tricks.com/creating-a-vs-code-theme/) by Sarah Drasner.
