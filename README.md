# Sweet Sidenotes
Sweet Sidenotes is a css snippet that allows you to get, via callouts, notes alongside the main text.

Table of content
1. [Introduction](#Introduction)
2. [How to install](#How-to-install)
3. [How to use](How-to-use)
4. [License](#License)

## Introduction

After doing some research, I found out about the existence of sidenotes, particularly tufte. I looked to see if there might already be a snippet for Obsidian somewhere, but I couldn't find it, so I decided to create it myself. Thus was born Sweet Sidenotes, a snippet that through callouts allows you to get an aesthetically beautiful sidenote.

## How to install

1. Download the CSS file from the css folder inside `<vault name>/.obsidian/snippets`.
2. Enable the snippets under the **Appearance** section in the settings.
3. Download the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin in order to customize the snippet and also to make it work.

## How to use

1. To create a sidenote callout you have to write [!sidenote] to the first line of a blockquote. To reverse their position you just put the left adjustment ([!sidenote|left]).

```
>[!sidenote]
>Ut consectetur diam lorem, ac consectetur eros imperdiet nec. Nunc quam sem, posuere at est nec, congue condimentum arcu.
```

or reversed

```
>[!sidenote|left]
>Quisque sodales mollis sodales. Morbi sem erat, gravida in velit in, fermentum consectetur neque.
```

![basic](https://github.com/user-attachments/assets/72d9ef7c-9766-4dcb-b7bb-3803b10418cc)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
