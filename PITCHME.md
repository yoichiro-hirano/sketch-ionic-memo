### Sketch & Ionic　について（アプリ開発R&Dの気づき）

- アプリ開発
- Sketch |
- Ionic |

---

### Sketch

## インストール
* 完全ビルドとruntime-only ビルド
特に何も設定しないとruntime-onlyとなる。軽量。
クライアントでテンプレートをコンパイルする必要がある (例えば、 template オプションに文字列を渡す、もしくは DOM 内の HTML をテンプレートとして利用し要素にマウントする) 場合は、コンパイラすなわち完全ビルドが必要。
完全ビルドしたい時はwebpack.config.jsの設定をする
```js
module.exports = {
  // ...
  resolve: {
    alias: {
      vue : 'vue/dist/vue.esm.js'
    }
  }
}
```


---


### 2枚目のスライド


---


### 3枚目のスライド


---


### END
