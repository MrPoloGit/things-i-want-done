# Completed

## Spice extension in Zed IDE

- **Stack:** Spice, Rust, JavaScript, Tree-sitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- Add Spice support, including all these types
  - Circuit Netlists: .cir, .sp, .spi (Standard text files listing components).
  - LTspice: .asc (Schematic), .asy (Symbol), .raw (Simulation Data).
  - Models/Libraries: .mod, .lib, .mdl.
  - NASA SPICE Kernels: .bsp (Binary SPK), .tpc (Text PCK), .tls (Leapseconds).
- Create tree-sitter-spice
- Create a language server
