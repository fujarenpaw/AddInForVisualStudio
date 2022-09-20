# AddInForVisualStudio

## 作りたいもの

他のエディタでは存在するが、Visualstudioのショートカットには存在しない機能があり、不便なので拡張機能として、導入したい。



- コメントアウト/解除

  VisualStudioでも存在しているが、ショートカットがそれぞれ別れている。

  2つもショートカット覚えたくないので、1つのキーで2つの機能が欲しい。VS codeには同様の機能がある。
  VS Code:editor.action.commentLine

- 下(上)の行にコピー
  選択した行をそのまま、下の行にコピーできる機能。
  ショートカットなしだと下記のようになるのですごい面倒。

  home -> shift +  end -> Ctrl + c -> right -> Ctrl + v -> enter
  こちらもVS codeに存在する。
  VS Code:editor.action.copyLinesDownAction

- 大文字小文字
  選択した変数などの大文字小文字の切り替え。
  こちらも2つのショートカットとしては存在するが、1つのキーとして導入したい。
  おそらくVS Codeにはなく、Intelij IDE系には存在。

- 下の行に改行
  行の真ん中を選択した状態からでも、改行できる。endボタンを押す手間が省けて地味に便利。

  おそらくVS Codeにはなく、Intelij IDE系には存在。



