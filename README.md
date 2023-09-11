# 创建 bun lib
```bash
bun create stock-vip/bun-lib

``` 

#  创建本地模版
```bash
mkdir $HOME/.bun-create
cd $HOME/.bun-create
bunx degit stock-vip/bun-lib lib

# 以后 可以直接
bun create lib  my-lib
```

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v0.6.3. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
