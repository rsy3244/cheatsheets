### Beamer用チートシート 
## preamble
```tex
\documentclass[dvipdfmx,12pt,notheorems]{beamer} %dvipdfmxを使う場合は指定
%%%% 和文用(よくわかってないです) %%%%
\usepackage{bxdpx-beamer} %ナビゲーションシンボル(?)を機能させる
\usepackage{pxjahyper} %しおりの日本語対応
\usepackage{minijs} %和文メトリックの調整
\renewcommand{\kanjifamilydefault}{\gtdefault} %和文規定をゴシックに(変えたければrenewcommand で調整)

%%%% スライドの見た目 %%%%%
\usetheme{Metropolis}
%\usefonttheme{professionalfonts}

%%%%% フォント基本設定 %%%%%
\usepackage[T1]{fontenc}%8bit フォント
\usepackage{textcomp}%欧文フォントの追加
\usepackage[utf8]{inputenc}%文字コードをUTF-8
\usepackage{otf}%otfパッケージ
\usepackage{lxfonts}%数式・英文ローマン体を Lxfont にする
\usepackage{bm}%数式太字
%%%%%%%%%%
```
