# Hello Go on Wasmer 🚀

Contoh aplikasi sederhana menggunakan **Go 1.24.5** yang dikompilasi ke **WebAssembly/WASI** lalu dijalankan di **Wasmer Cloud**.

## Build lokal
```bash
GOOS=wasip1 GOARCH=wasm go build -o hello.wasm hello.go
