# Aria Maestosa patchs for modern MacOS

A set of patches and build fixes to compile and run **[Aria Maestosa](http://ariamaestosa.sourceforge.net/)** (an open-source MIDI tracker/sequencer) on modern Mac.

## Key Changes / What's Fixed

- Fixed compilation errors on modern macOS environments.
- Updated build scripts for modern environments.

## Usage & Build Instructions

1. Download the original source code (`AriaSrc-1.4.13.tar.bz2`) from [SourceForge](https://sourceforge.net/projects/ariamaestosa/).
2. Extract the archive and apply this patch:

```bash
tar jxvf AriaSrc-1.4.13.tar.bz2
cd AriaSrc-1.4.13
patch -p1 < /path/to/AriaSrc-1.4.13.patch
```

## Credits

[Original software](https://sourceforge.net/projects/ariamaestosa/) created by [mmg1](https://sourceforge.net/u/mmg1/profile/).


# 最近のMacで Aria Maestosa を動作させるためのパッチ

## 変更点

- 最近のビルド環境でビルドできるように（SConstruct）
- 最近のMacの環境でビルドできて、動作するように

## このパッチの利用法

1. オリジナルのソースコード(`AriaSrc-1.4.13.tar.bz2`)を[SourceForge](https://sourceforge.net/projects/ariamaestosa/)からダウンロードしてください。
2. 上記を展開後、このパッチを当ててください。

```bash
tar jxvf AriaSrc-1.4.13.tar.bz2
cd AriaSrc-1.4.13
patch -p1 < /path/to/AriaSrc-1.4.13.patch
```

あとは比較的素直にできるはず。

## 制限事項
- 4Kモニターで表示すると、表示が崩れます
- 「オーディオファイルに出力」が機能しません
