# zed-log

Syntax highlighting for log files in [Zed](https://github.com/zed-industries/zed).

![image.png](https://s2.loli.net/2024/03/29/dVPXl1m5Z8JFQ7R.png)

### Test locally

- Clone this repo: `git clone https://github.com/evrensen467/zed-log log`
- Clone the [tree-sitter-log](https://github.com/Tudyx/tree-sitter-log) repo: `https://github.com/Tudyx/tree-sitter-log`
- CD into the repo: `cd tree-sitter-log`
- Build the WASM: `tree-sitter build-wasm` (might require docker-engine running)
- Rename the WASM file to `log.wasm`
- Move the WASM file into `log/grammars` (this repository)
- Move the `log`repository to `~/Library/Application Support/Zed/extensions/installed`
