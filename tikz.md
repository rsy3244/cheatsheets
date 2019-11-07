# tikz用チートシート
## option

## expression
- foreach
```tex
\foreach {変数} [オプション] in {レンジ} {
  %statement
}

%例
\foreach \x [count=\i from 0] in {0.0, 0.5, ..., 4.0} {
  \node(a\i) at (\x, 2.5) {$a_\i$};
}
```
### オプションで利用できるもの
 - count `[count=\i from 0]`
  ループ毎に`from`で指定した値にインクリメントする 
 - evaluate `[eavluate=\x as \y using \x\*\x]` 
  変数に対して`using`で評価した値を代入する
