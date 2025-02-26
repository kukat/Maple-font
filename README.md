![](/img/head.svg)

# Maple Series V5

[中文版](/README_CN.md)

## What's new compare to V4

- redesigned it according to `Fira Code Retina`'s spacing and glyph and expand the font width from 600 to 1200, which lead to a **better rendering effect** on my screen(1080P)
  - v4: ![](/img/sizechange.gif)
  - v5: ![](/img/sizechange1.gif)
- change glyph shape for **more comfortable reading experience**
- add `..`,`...` ligature

## What's next

Changes will publish in pre-release

- [x] add **Light** and **LightItalic** weight
- [x] thick **Bold** and **BoldItalic** weight
- [x] adjust kerning
- [ ] modify glyphs

## Download

in Release

[国内地址](https://gitee.com/subframe7536/Maple/releases/v5.0)

## Maple Mono

Open source rounded Monospace font

- inspired by [Source Code Pro](https://github.com/adobe-fonts/source-code-pro), [Fira Code Retina](https://github.com/tonsky/FiraCode), ubuntu mono, operator mono, [sarasa mono sc nerd](https://github.com/laishulu/Sarasa-Mono-SC-Nerd) and so on
- modify `@ # $ % &` shape
- only contains latin, table control characters and few symbols
- with **ligatures**
- **cursive** style
- `source/mono.fea`: more readable OpenType Script

### Maple Mono NF

~~Font for Cli, Maple Mono mixing Nerd Fonts~~
no longer provide, please read [Nerd Fonts Docs](https://github.com/ryanoasis/nerd-fonts#option-8-patch-your-own-font)

- I use

```shell
font-patcher -l -s --careful -c -w /path/to/ttf
```

### Sample

#### Total

![](img/base.png)

#### Ligature

no `==` `===` `>=` `<=` and more ligatures with `=` for recognition

![](img/ligature.png)
![](img/ligature.gif)

#### Cli

![](img/code_sample/cli.webp)

#### React

![](img/code_sample/react.webp)

#### Vue

![](img/code_sample/vue.webp)

#### Java

![](img/code_sample/java.webp)

#### Go

![](img/code_sample/go.webp)

#### Python

![](img/code_sample/python.webp)

#### Rust

![](img/code_sample/rust.webp)

## Dev

### usage

python fonttools

### build

```
git clone https://github.com/subframe7536/Maple-font
cd Maple-font/source
pip install fonttools
python build.py
```

## License

SIL Open Font License 1.1
