# nushell-adventure

### 7/1/25
1. Depois de instalar e começar a usar, o `ping` nao funcionava! top!
1. Encontrei este [guia](https://fuzzyblog.io/blog/nushell/2022/07/17/getting-nushell-usable-under-osx-for-myself.html) e vi que no path faltavam ainda mais paths! 2x top!
1. Ele indica para alterar o `/Users/marte/Library/Application Support/nushell/config.nu`, adicionando os paths necessários com o seguinte código `let-env PATH = ($env.PATH | append "/usr/local/bin")
`, mas não deu pq let-env nao existe! (??) 3x top!
1. Dps vi nos [docs da nushell como adicionar corretamente](https://www.nushell.sh/book/environment.html#env-var-assignment), `$env.Path = ($env.PATH | append "/sbin")`

