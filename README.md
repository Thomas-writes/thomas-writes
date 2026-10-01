# `thomas-writes`

```text
thomas@github:~$ whoami

CS + Mathematics @ University of Kansas
Interested in compilers, operating systems,
computer architecture, and embedded systems.

Currently somewhere inside gcc/cc1.
```

---

## `~/about`

I'm a Computer Science and Mathematics student interested in understanding what happens **below the abstraction layer**.

Most of what I'm interested in lives somewhere between source code and silicon:

```text
        source
          │
          ▼
     ┌─────────┐
     │ compiler│
     └────┬────┘
          │
          ▼
    optimization
          │
          ▼
      assembly
          │
          ▼
  ┌───────────────┐
  │ CPU / hardware│
  └───────────────┘
```

Current interests:

```text
[+] Compilers
[+] Operating Systems
[+] Systems Architecture
[+] Embedded Systems
[+] Programming Languages
```

---

## `~/current-rabbit-hole`

### GCC Internals

Currently investigating how GCC's optimization pipeline changes between optimization levels.

```text
C
│
▼
cc1
│
├── GENERIC
│
├── GIMPLE
│
├── SSA
│
├── Tree / IPA Optimizations
│
├── RTL
│
├── Register Allocation
│
└── Assembly
```

So far I've:

- built **GCC from source** with debugging information
- stepped directly through `cc1` using **LLDB**
- traced GCC's optimization state through `global_options.x_optimize`
- compared optimization passes between `-O0`, `-O1`, `-O2`, and `-O3`
- explored how command-line optimization options alter GCC's internal pipeline

```c
/* me, probably */
while (understanding_gcc < 100) {
    read_source();
    set_breakpoint();
    stare_at_gimple();
}
```

---

## `~/stack`

### Languages

![C](https://img.shields.io/badge/C-111111?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-111111?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-111111?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-111111?style=for-the-badge&logo=openjdk&logoColor=white)

### Tools / Systems

![GCC](https://img.shields.io/badge/GCC-111111?style=for-the-badge&logo=gnu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-111111?style=for-the-badge&logo=cmake&logoColor=white)
![LLVM](https://img.shields.io/badge/LLDB-111111?style=for-the-badge&logo=llvm&logoColor=white)

---

## `~/projects`

### 🔬 GCC Optimization Research

Exploring the internals of GCC's optimization system and compiler pipeline.

**Working with**

`C++` · `GCC` · `LLDB` · `GIMPLE` · `RTL` · `SSA`

---

### 🩺 HealthSense

**HackUTD 2025**

Hackathon project focused on health technology.

---

### 🎵 Spot-a-Song

**HackKU**

Music-focused hackathon project.

---

## `~/stats`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=thomas-writes&show_icons=true&hide_border=true&theme=transparent" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thomas-writes&layout=compact&hide_border=true&theme=transparent" />
</p>

---

## `~/activity`

<p align="center">
  <img src="https://streak-stats.demolab.com?user=thomas-writes&theme=transparent&hide_border=true" />
</p>

---

## `~/currently`

```text
research  ██████████████░░  GCC internals
systems   ████████████░░░░  OS / architecture
embedded  █████████░░░░░░░  hardware experiments
sleep     ██░░░░░░░░░░░░░░  segmentation fault
```

---

## `~/contact`

```bash
$ git clone https://github.com/thomas-writes
$ cd thomas-writes
$ cat README.md
```

**GitHub:** [github.com/thomas-writes](https://github.com/thomas-writes)

---

<p align="center">
  <code>compile. debug. understand.</code>
</p>
