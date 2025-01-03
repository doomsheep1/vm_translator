# VM Translator
Nand2Tetris course virtual machine language translator written in rust. Takes vm files written in Nand2Tetris vm language and outputs it in hack assembly language

# Test
cargo test

# Build
cargo build --release

# Usage
Run the following which will output a <file_name>.asm file<br>
./vm_translator <file_name>.vm or ./vm_translator <directory_containing_vm_files> (if built)<br>
cargo run <file_name>.vm or cargo run <directory_containing_vm_files> (if not built)
