インストール方法(MAC OX)

```
$ brew install elixir
```

バージョン確認

```
$ elixir -v
Erlang/OTP 20 [erts-9.2] [source] [64-bit] [smp:8:8] [ds:8:8:10] [async-threads:10] [hipe] [kernel-poll:false] [dtrace]

Elixir 1.6.0 (compiled with OTP 20)
```

HelloWorld

```
$ cat hello.exs 
defmodule Hello do
    def world do
        IO.puts "Hello world"
    end
end

Hello.world
$ elixir hello.exs 
Hello world
```
