# Remmen GSUB Demo

![Remmen GSUB Demo](documentation/header.png)

モリサワのBIZ UD明朝は、教育やビジネス文書作成などに活用できるよう、より多くの方にとって読みやすく使いやすいように設計されたユニバーサルデザインフォントです。BIZ UD明朝をベースとした技術サンプルとして、連綿体フォントを設計しました。

BIZ UD Mincho is a universal design typeface designed to be easy to read and ideal for education and business documentation. We designed a Remmen-tai (Japanese script) font as a technical sample based on BIZ UD Mincho.

Download the latest version of the fonts [from the releases page](https://github.com/morisawa-inc/remmen-gsub-demo/releases).

## About Morisawa

モリサワは、1924 年に世界に先駆けて邦文写真植字機を発明して以来、一貫してタイポグラフィの未来をみつめて研究開発を続けているフォントメーカーです。日本語および多言語フォント 1,500 書体以上が使えるフォントライセンス製品をはじめ、web フォントや組込みフォント、多言語ユニバーサル情報配信ツールなどを提供しています。

Morisawa Inc. is Japan’s leading font foundry that has never wavered from its commitment to undertaking research and development in typography since its invention of the first Japanese phototypesetting machine in 1924. The company provides font licenses for over 1,500 typefaces of Japanese and multi-script, web font services, embedded fonts, and multilingual e-magazine/book solution services.


## Building

If you want to build fonts manually on your own computer:

* `cd fonts && sh ./build.sh` will produce a font file using your local Python environment. Note that you should `pip install afdko=4.0.0` before production.
* `sh ./build_font.sh` will produce a font file using docker, which automatically set up development environment in a docker image and produce a font file.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
