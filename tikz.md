### tikz用チートシート
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
