# This is a file encryptor and decryptor which uses a cryptographic key uses `byte_shift()`.

### Cloning the repo
- You need to have Rust installed on your system and an example file
- 
```bash
git clone https://github.com/SkyWarrior123/naive_file_encryptor.git
```
- 
```bash
cargo build
cargo run <filename> <false=encryption/ true=decryption>
```

- For using the file in the example. Run the following command.
```bash For encryption
cargo run imp.txt false
```
```bash For decryption
cargo run imp.txt true
```