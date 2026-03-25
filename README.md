# 🦀 Rust WASM UI: The Bare-Metal Web Presentation Lab

> **"Unleash native performance in the browser with Rust safety and WASM efficiency."**

Repositori ini adalah **Blueprint Utama (Rak 03)** dalam ekosistem *The Learning Matrix*. Fokus utamanya adalah membedah arsitektur antarmuka performa tinggi melalui **WebAssembly (WASM)** menggunakan framework **Leptos** dan **Yew**.

---

## 🎯 Visi Arsitektural: Hardware-Accelerated UI (The Why)
Rust WASM UI Lab berfokus pada melampaui batasan JIT compilation dan Garbage Collection di browser:
1.  **Deterministic Performance (The Engine)**: Bagaimana biner Rust dieksekusi secara presisi tanpa interupsi runtime.
2.  **Memory Safety in UI (The Shield)**: Penggunaan sistem ownership Rust untuk mengelola alokasi memori linear di WASM.
3.  **Low-Level Interoperability (The Bridge)**: Mekanisme FFI untuk komunikasi super cepat antara JS dan Rust.

Visi repositori ini adalah membedah **The Rust Web Ecosystem**:
1. **Next-Gen Reactivity**: Penggunaan *Signals* (Leptos) untuk pembaruan DOM tanpa Virtual DOM.
2. **Binary Optimization**: Strategi pengecilan ukuran biner WASM dan optimasi instruksi mesin.
3. **Heavy-Compute UI**: Implementasi modul rendering, simulasi fisika, dan editor kompleks di peramban.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: Rust (Logic Core).
- **Sumbu-X**: RAK-02 (Execution Hub / Browser) ➡️ **RAK-03 (Digital UI Hub)**.

Di sini kita belajar **"Bagaimana mendorong batas-batas performa web melalui biner murni"**.

---

## 🏗️ Struktur 8-Rak (The Taxonomy)
1. **RAK-01: Anatomy & Landscape** (Evolusi WASM, Rust vs JS for Heavy Tasks).
2. **RAK-02: Foundation & Core Rules** (Rust-WASM Toolchain: wasm-pack & cargo-leptos).
3. **RAK-03: Evolution & Interfacing** (DOM Bindings with `web-sys` & `js-sys`).
4. **RAK-04: Core Mechanics & Internals** (Linear Memory Management, Tables, & Memory Leak Prevention).
5. **RAK-05: Ecosystem & Tooling** (Yew, Leptos, Dioxus, & Integration with Vite/Webpack).
6. **RAK-06: The Underworld** (Atomic Ops, SharedArrayBuffer, & Multi-threaded WASM).
7. **RAK-07: Specialization** (WASM Plugins, Canvas/WebGL Rendering, & Crypto in Browser).
8. **RAK-08: Matrix Intersection** (The Bridge: How Rust UI talks to Python/Go Services).

---

## 📊 Status Proyek
Detail status per Rak dapat dilihat di [status.md](./status.md).

> [!NOTE]
> Proyek ini mengikuti standar dokumentasi **Gold Standard PPM V4**.

- `README.md` adalah pendahuluan ini.
- `docs/` berisi dokumentasi pendukung.
- `RAK-xx/` berisi semua rak utama.

## Dokumentasi
- [docs/root-governance.md](./docs/root-governance.md)