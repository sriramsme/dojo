## Projects

See PROJECTS.md for the seeded catalog: emulators, ray tracers, shells,
mallocs, bytecode VMs, CUDA kernels. Custom ideas welcome - the catalog is
a starting grid, not a fence.

## FAQ

- Can I use AI normally everywhere else? Yes. This is a gym, not a monastery.
- Can the agent help with toolchain errors? Yes - explaining and diagnosing
  is coaching. Writing the fix is not.
- What if I am truly stuck? Rung 4 of the hint ladder is pseudocode. Real
  understanding survives; typing remains yours.
  PROJECTS.md

# Project Catalog

A sample menu, not a syllabus. These entries demonstrate what a good project
pitch looks like - difficulty rating, concepts taught, a small first milestone,
canonical resources - and double as proven starting points. Your own interests
drive the actual pick: during first boot, brainstorm with your agent and treat
any entry here as inspiration or format reference, not obligation. Custom
projects outside this list are first-class citizens.

Difficulty: 1 = friendly first C/Rust project, 2 = comfortable with
pointers/builds, 3 = multi-week commitment. Every entry names a first
milestone so any project starts with an early win.

## Emulation track

- CHIP-8 emulator (C) - difficulty 1. Teaches fetch-decode-execute, memory
  maps, display buffers. First milestone: render the fontset. Resource:
  CHIP-8 technical reference (tobiasvl.github.io).
- Game Boy emulator (Rust) - difficulty 3. Teaches real CPU semantics,
  interrupts, memory banking. First milestone: boot ROM logo appears.
  Resource: Pan Docs.

## Graphics track

- Ray tracer in one weekend (C, later Rust + SIMD) - difficulty 2. Teaches
  vector math, perf profiling, auto/hand vectorization. First milestone:
  one blue-white gradient sphere. Resource: Ray Tracing in One Weekend.
- Software rasterizer (C/Rust) - difficulty 2. Teaches projection, clipping,
  z-buffering: what GPUs do in hardware. First milestone: wireframe cube.
- Path tracer (any) - difficulty 3. Teaches Monte Carlo methods, importance
  sampling. First milestone: cornell box, noisy but converging.

## Systems track

- Unix shell (C) - difficulty 2. Teaches processes, fork/exec, pipes, job
  control: everything from our process/thread discussions hands-on. First
  milestone: run external commands with arguments.
- HTTP server from raw sockets (C/Rust/Go-free) - difficulty 2. Teaches
  sockets, parsing, concurrency models (thread pool vs event loop - build both).
  First milestone: serve one hardcoded page.
- Malloc replacement (C) - difficulty 3. Teaches allocators, alignment,
  fragmentation. Benchmark against glibc malloc with hyperfine.
  First milestone: bump allocator passing basic tests.
- Key-value store with WAL (Rust) - difficulty 3. Teaches B-trees, crash
  consistency, fsync semantics - directly deepens Neon-level intuition.
  First milestone: get/set surviving kill -9.
- Mini git (any) - difficulty 2. Teaches content-addressed storage, hashing,
  DAGs. First milestone: init/hash-object/cat-file.

## Languages track

- Bytecode VM / Lox interpreter (C or Rust) - difficulty 2-3. Teaches
  compilers, stacks, closures, garbage collection. Resource: Crafting
  Interpreters. First milestone: REPL evaluating arithmetic.
- Regex engine (any) - difficulty 2. Teaches automata, backtracking vs NFA.
  First milestone: literal and star matching.
- Lisp in a weekend (Rust) - difficulty 1. Teaches parsers, eval/apply.
  First milestone: arithmetic REPL.

## Performance/GPU track (cloud GPU via Colab/vast.ai)

- CUDA matmul ladder (C++) - difficulty 3. Teaches SIMT, shared memory,
  occupancy. Climb from naive kernel toward cuBLAS. Resource: PMPP 4th ed
  - Simon Boehm's matmul post. First milestone: naive kernel beats CPU loop.
