GASHA
====
**Gakimaru's researched and standard library for C++**  
Copyright (c) 2014 Itagaki Mamoru  
Released under the [MIT license][MIT].
<https://github.com/gakimaru/gasha_proj/blob/master/LICENSE>
[MIT]: http://www.opensource.org/licenses/mit-license.php

ライブラリファイルビルド用リポジトリ
---
このリポジトリは、「GASHA」のソースファイルからライブラリ
ファイルを作成するために使用します。  
> とくに必要なソースファイルやプロジェクトファイルがあるわけ
> ではなく、サブモジュールにより、各リポジトリを適切な位置関
> 係に配置するためにのみ使用するリポジトリです。  
> 
> 通常は、ソース用のリポジトリがあればライブラリをビルドでき
> るため、このリポジトリは不要です。  
> 
> しかし、共同開発メンバーに対して、ソースコードを非公開で
> ライブラリを提供するような場合、ライブラリファイルを手早く
> ビルドするために、このリポジトリを利用することができます。
> 
> **リポジトリ構成**
> * [`gasha` ライブラリ本体用リポジトリ][gasha]  
>   ヘッダーファイルとライブラリファイル  
> * [`gasha_settings` ライブラリ挙動設定用リポジトリ][gasha_settings]  
>   プロジェクト固有の挙動設定用のヘッダーファイル  
> * [`gasha_src` ライブラリソース用リポジトリ][gasha_src]  
>   ライブラリのソースファイルとビルド用プロジェクト  
> * [`gasha_examples` サンプルプログラム用リポジトリ][gasha_examples]  
>   多数のサンプルプログラム用プロジェクト  
>   ライブラリとソースをサブモジュール配置  
> * [`gasha_proj` ライブラリビルド用リポジトリ][gasha_proj]  
>   ライブラリとソースをサブモジュール配置  
[gasha]: https://github.com/gakimaru/gasha
[gasha_settings]: https://github.com/gakimaru/gasha_settings
[gasha_src]: https://github.com/gakimaru/gasha_src
[gasha_examples]: https://github.com/gakimaru/gasha_examples
[gasha_proj]: https://github.com/gakimaru/gasha_proj

「GASHA」とは？
---
詳しくは、「GASHA」の[サンプルプログラム][SAMPLE]に記述しています。
[SAMPLE]: https://github.com/gakimaru/gasha_examples/blob/master/README.md

■■以上
