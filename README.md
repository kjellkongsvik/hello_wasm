pip3 install wasmtime
# https://rustwasm.github.io/wasm-pack/installer/
export WASM_INTERFACE_TYPES=1
wasm-pack build
cp pkg/hello_wasm.wasm .
python3 hello.py
