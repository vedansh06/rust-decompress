🦀 rust-decompress

A minimal, fast and simple ZIP decompression tool written in Rust. 🚀

✨ Features

- Extracts .zip archives 📦
- Automatically creates directories 📁
- Preserves file structure and comments 📝
- Displays extracted file sizes 📏
- Lightweight & fast ⚡
- Written entirely in Rust 🦀

📥 Installation

Clone & build:

```js
git clone https://github.com/<your-user>/rust-decompress.git
cd rust-decompress
cargo build --release
```

🧰 Usage

Just run:

```js
cargo run <archive.zip>
```

Example:

```js
cargo run samples/test.zip
```

📤 Output

Example terminal output:

```js
File 0 extracted to "docs/"
File 1 extracted to "docs/info.txt" (142 bytes)
File 2 extracted to "readme.md" (540 bytes)
File 3 comment: Important license info
```