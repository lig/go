* [misc/chrome/gophertool/gopher.js:35](misc/chrome/gophertool/gopher.js#L35): make this smarter, using a list of packages + substring matches.
* [src/archive/tar/fuzz_test.go:76](src/archive/tar/fuzz_test.go#L76): We may want to check if the archive roundtrips. This would require
* [src/archive/tar/stat_unix.go:97](src/archive/tar/stat_unix.go#L97): Implement solaris (see https://golang.org/issue/8106)
* [src/archive/zip/fuzz_test.go:79](src/archive/zip/fuzz_test.go#L79): We may want to check if the archive roundtrips.
* [src/bytes/bytes.go:1378](src/bytes/bytes.go#L1378): if large prefixes of sep are matching
* [src/bytes/bytes.go:803](src/bytes/bytes.go#L803): update when package unicode captures more of the properties.
* [src/cmd/api/main_test.go:427](src/cmd/api/main_test.go#L427): ReleaseTags (need to load default)
* [src/cmd/asm/internal/asm/asm.go:24](src/cmd/asm/internal/asm/asm.go#L24): configure the architecture
* [src/cmd/asm/internal/asm/operand_test.go:360](src/cmd/asm/internal/asm/operand_test.go#L360): Should make * illegal here; a simple alias for JMP AX.
* [src/cmd/asm/internal/asm/parse.go:562](src/cmd/asm/internal/asm/parse.go#L562): Rethink how we handle ARM register shifts to be
* [src/cmd/asm/internal/asm/parse.go:6](src/cmd/asm/internal/asm/parse.go#L6): Split apart?
* [src/cmd/asm/internal/asm/parse.go:985](src/cmd/asm/internal/asm/parse.go#L985): Consistency in the encoding would be nice here.
* [src/cmd/asm/internal/asm/testdata/386.s:46](src/cmd/asm/internal/asm/testdata/386.s#L46): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/386.s:51](src/cmd/asm/internal/asm/testdata/386.s#L51): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/386.s:56](src/cmd/asm/internal/asm/testdata/386.s#L56): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/amd64.s:57](src/cmd/asm/internal/asm/testdata/amd64.s#L57): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/amd64.s:65](src/cmd/asm/internal/asm/testdata/amd64.s#L65): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/amd64.s:73](src/cmd/asm/internal/asm/testdata/amd64.s#L73): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/amd64.s:81](src/cmd/asm/internal/asm/testdata/amd64.s#L81): This line is silently dropped on the floor!
* [src/cmd/asm/internal/asm/testdata/arm.s:108](src/cmd/asm/internal/asm/testdata/arm.s#L108): classifying foo(SB) as C_TLS_LE
* [src/cmd/asm/internal/asm/testdata/arm64.s:372](src/cmd/asm/internal/asm/testdata/arm64.s#L372): this could have better encoding
* [src/cmd/asm/internal/asm/testdata/loong64.s:6](src/cmd/asm/internal/asm/testdata/loong64.s#L6): cover more instruction
* [src/cmd/asm/internal/asm/testdata/ppc64.s:263](src/cmd/asm/internal/asm/testdata/ppc64.s#L263): cleanup inconsistency of printing CMPx opcodes with explicit CR arguments.
* [src/cmd/asm/internal/asm/testdata/ppc64.s:44](src/cmd/asm/internal/asm/testdata/ppc64.s#L44): These are preprocessed by the assembler into MOVD $const>>shift, R5; SLD $shift, R5.
* [src/cmd/asm/internal/asm/testdata/ppc64.s:50](src/cmd/asm/internal/asm/testdata/ppc64.s#L50): On GOPPC64={power8,power9}, this is preprocessed into MOVD $-1, R5; RLDC R5, $33, $63, R5.
* [src/cmd/asm/internal/lex/slice.go:61](src/cmd/asm/internal/lex/slice.go#L61): Col is only called when defining a macro and all it cares about is increasing
* [src/cmd/cgo/gcc.go:1028](src/cmd/cgo/gcc.go#L1028): Note that this fails if nil is shadowed.
* [src/cmd/cgo/gcc.go:1067](src/cmd/cgo/gcc.go#L1067): Handle types defined within function.
* [src/cmd/cgo/gcc.go:1363](src/cmd/cgo/gcc.go#L1363): This ignores shadowing.
* [src/cmd/cgo/gcc.go:2697](src/cmd/cgo/gcc.go#L2697): should probably base this on field alignment.
* [src/cmd/cgo/gcc.go:2810](src/cmd/cgo/gcc.go#L2810): it would be safer to only do this if
* [src/cmd/cgo/gcc.go:3092](src/cmd/cgo/gcc.go#L3092): Handle fields that are anonymous structs by
* [src/cmd/cgo/gcc.go:3315](src/cmd/cgo/gcc.go#L3315): Currently our best solution is to find these manually and list them as
* [src/cmd/cgo/internal/test/callback.go:202](src/cmd/cgo/internal/test/callback.go#L202): use runtime.CallersFrames
* [src/cmd/cgo/internal/test/callback_windows.go:65](src/cmd/cgo/internal/test/callback_windows.go#L65): support SEH on other architectures.
* [src/cmd/cgo/internal/testcshared/cshared_test.go:425](src/cmd/cgo/internal/testcshared/cshared_test.go#L425): deduplicate this struct from cmd/link/internal/ld/pe.go
* [src/cmd/cgo/internal/testfortran/fortran_test.go:32](src/cmd/cgo/internal/testfortran/fortran_test.go#L32): This duplicates but also diverges from logic from cmd/go
* [src/cmd/cgo/out.go:1465](src/cmd/cgo/out.go#L1465): Handle types defined within a function.
* [src/cmd/compile/internal/amd64/ssa.go:1036](src/cmd/compile/internal/amd64/ssa.go#L1036): use MOVQreg for reg->reg copies instead of OpCopy?
* [src/cmd/compile/internal/amd64/ssa.go:1267](src/cmd/compile/internal/amd64/ssa.go#L1267): We currently use the 2-byte instruction TESTB AX, (reg).
* [src/cmd/compile/internal/amd64/versions_test.go:105](src/cmd/compile/internal/amd64/versions_test.go#L105): go tool objdump doesn't disassemble the bmi1 instructions
* [src/cmd/compile/internal/amd64/versions_test.go:123](src/cmd/compile/internal/amd64/versions_test.go#L123): we're depending on platform-native objdump here. Hence the Skipf
* [src/cmd/compile/internal/arm/ssa.go:871](src/cmd/compile/internal/arm/ssa.go#L871): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/base/flag.go:127](src/cmd/compile/internal/base/flag.go#L127): remove
* [src/cmd/compile/internal/base/flag.go:478](src/cmd/compile/internal/base/flag.go#L478): Test and delete this condition.
* [src/cmd/compile/internal/base/flag.go:482](src/cmd/compile/internal/base/flag.go#L482): fix races and enable the following flags
* [src/cmd/compile/internal/base/hashdebug.go:141](src/cmd/compile/internal/base/hashdebug.go#L141): Delete when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:175](src/cmd/compile/internal/base/hashdebug.go#L175): Delete remainder of function when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:210](src/cmd/compile/internal/base/hashdebug.go#L210): Delete when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:220](src/cmd/compile/internal/base/hashdebug.go#L220): Delete when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:236](src/cmd/compile/internal/base/hashdebug.go#L236): Delete when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:339](src/cmd/compile/internal/base/hashdebug.go#L339): Delete rest of function body when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:391](src/cmd/compile/internal/base/hashdebug.go#L391): Delete varname parameter when we switch to bisect-only.
* [src/cmd/compile/internal/base/hashdebug.go:416](src/cmd/compile/internal/base/hashdebug.go#L416): Delete rest of function when we switch to bisect-only.
* [src/cmd/compile/internal/inline/inl.go:1110](src/cmd/compile/internal/inline/inl.go#L1110): Refactor to keep a reference so this can all be done
* [src/cmd/compile/internal/inline/inl.go:590](src/cmd/compile/internal/inline/inl.go#L590): in the case of a single-call closure, the inlining budget here is potentially much, much larger.
* [src/cmd/compile/internal/inline/inlheur/funcprops_test.go:35](src/cmd/compile/internal/inline/inlheur/funcprops_test.go#L35): decide whether to convert this
* [src/cmd/compile/internal/inline/inlheur/score_callresult_uses.go:155](src/cmd/compile/internal/inline/inlheur/score_callresult_uses.go#L155): add an assert/panic here.
* [src/cmd/compile/internal/ir/expr.go:930](src/cmd/compile/internal/ir/expr.go#L930): handle initial declaration not including an assignment and
* [src/cmd/compile/internal/liveness/arg.go:234](src/cmd/compile/internal/liveness/arg.go#L234): include other store instructions?
* [src/cmd/compile/internal/liveness/plive.go:1338](src/cmd/compile/internal/liveness/plive.go#L1338): consider trimming leading zeros.
* [src/cmd/compile/internal/liveness/plive.go:758](src/cmd/compile/internal/liveness/plive.go#L758): if the output parameter is heap-allocated, then we
* [src/cmd/compile/internal/loong64/ssa.go:946](src/cmd/compile/internal/loong64/ssa.go#L946): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/mips/ssa.go:808](src/cmd/compile/internal/mips/ssa.go#L808): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/mips64/ssa.go:817](src/cmd/compile/internal/mips64/ssa.go#L817): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/noder/noder.go:263](src/cmd/compile/internal/noder/noder.go#L263): maybe make the name optional? It was once mentioned on proposal 65199.
* [src/cmd/compile/internal/objw/prog.go:209](src/cmd/compile/internal/objw/prog.go#L209): this is an artifact of how funcpctab combines information for instructions at a single PC.
* [src/cmd/compile/internal/ppc64/ssa.go:1979](src/cmd/compile/internal/ppc64/ssa.go#L1979): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/ppc64/ssa.go:1997](src/cmd/compile/internal/ppc64/ssa.go#L1997): need to work FP comparisons into block jumps
* [src/cmd/compile/internal/ppc64/ssa.go:2045](src/cmd/compile/internal/ppc64/ssa.go#L2045): The second branch is probably predict-not-taken since it is for FP unordered
* [src/cmd/compile/internal/ppc64/ssa.go:2063](src/cmd/compile/internal/ppc64/ssa.go#L2063): The second branch is probably predict-not-taken since it is for FP unordered
* [src/cmd/compile/internal/rangefunc/rewrite.go:527](src/cmd/compile/internal/rangefunc/rewrite.go#L527): Could call runtime.deferrangefuncend after f.
* [src/cmd/compile/internal/reflectdata/reflect.go:1309](src/cmd/compile/internal/reflectdata/reflect.go#L1309): bss?
* [src/cmd/compile/internal/reflectdata/reflect.go:1360](src/cmd/compile/internal/reflectdata/reflect.go#L1360): make sure the linker deduplicates them (see dupok in writeType above).
* [src/cmd/compile/internal/reflectdata/reflect.go:1459](src/cmd/compile/internal/reflectdata/reflect.go#L1459): instantiations at least know the shape of the instantiated
* [src/cmd/compile/internal/reflectdata/reflect.go:779](src/cmd/compile/internal/reflectdata/reflect.go#L779): use rttype.Type for Elem() is ANY?
* [src/cmd/compile/internal/riscv64/ssa.go:779](src/cmd/compile/internal/riscv64/ssa.go#L779): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/rttype/rttype.go:122](src/cmd/compile/internal/rttype/rttype.go#L122): there's no mechanism to distinguish different pointer types,
* [src/cmd/compile/internal/rttype/rttype.go:239](src/cmd/compile/internal/rttype/rttype.go#L239): ability to switch len&cap. Maybe not needed here, as every caller
* [src/cmd/compile/internal/s390x/ssa.go:856](src/cmd/compile/internal/s390x/ssa.go#L856): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/s390x/ssa.go:922](src/cmd/compile/internal/s390x/ssa.go#L922): take into account Likely property for forward/backward
* [src/cmd/compile/internal/ssa/README.md:130](src/cmd/compile/internal/ssa/README.md#L130): can we come up with a shorter example that still shows the control flow?
* [src/cmd/compile/internal/ssa/README.md:182](src/cmd/compile/internal/ssa/README.md#L182): Probably explain here why the ordering of the passes matters, and why some
* [src/cmd/compile/internal/ssa/README.md:215](src/cmd/compile/internal/ssa/README.md#L215): need more ideas for this section
* [src/cmd/compile/internal/ssa/README.md:235](src/cmd/compile/internal/ssa/README.md#L235): more tips and info could likely go here
* [src/cmd/compile/internal/ssa/_gen/386.rules:379](src/cmd/compile/internal/ssa/_gen/386.rules#L379): Should the optimizations be a separate pass?
* [src/cmd/compile/internal/ssa/_gen/386.rules:741](src/cmd/compile/internal/ssa/_gen/386.rules#L741): DIVxU also.
* [src/cmd/compile/internal/ssa/_gen/386.rules:880](src/cmd/compile/internal/ssa/_gen/386.rules#L880): since we got rid of the W/B versions, we might miss
* [src/cmd/compile/internal/ssa/_gen/386.rules:890](src/cmd/compile/internal/ssa/_gen/386.rules#L890): more of this
* [src/cmd/compile/internal/ssa/_gen/386.rules:904](src/cmd/compile/internal/ssa/_gen/386.rules#L904): more of this
* [src/cmd/compile/internal/ssa/_gen/386Ops.go:406](src/cmd/compile/internal/ssa/_gen/386Ops.go#L406): sign-extending indexed loads
* [src/cmd/compile/internal/ssa/_gen/386Ops.go:412](src/cmd/compile/internal/ssa/_gen/386Ops.go#L412): add size-mismatched indexed loads, like MOVBstoreidx4.
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1181](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1181): more?
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1253](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1253): DIVxU also.
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1366](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1366): since we got rid of the W/B versions, we might miss
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1382](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1382): more of this
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1416](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1416): more of this
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1485](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1485): add indexed variants?
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1516](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1516): merging LEAQ doesn't work, assembler doesn't like the resulting instructions.
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:1523](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L1523): merging LEAQ doesn't work, assembler doesn't like the resulting instructions.
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:559](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L559): most runtime uses of atomic stores don't need that property.  Use normal stores for those?
* [src/cmd/compile/internal/ssa/_gen/AMD64.rules:608](src/cmd/compile/internal/ssa/_gen/AMD64.rules#L608): Should the optimizations be a separate pass?
* [src/cmd/compile/internal/ssa/_gen/AMD64Ops.go:1031](src/cmd/compile/internal/ssa/_gen/AMD64Ops.go#L1031): have these return flags instead of bool.  The current system generates:
* [src/cmd/compile/internal/ssa/_gen/AMD64Ops.go:776](src/cmd/compile/internal/ssa/_gen/AMD64Ops.go#L776): should we have generic versions of these?
* [src/cmd/compile/internal/ssa/_gen/AMD64Ops.go:854](src/cmd/compile/internal/ssa/_gen/AMD64Ops.go#L854): add size-mismatched indexed loads/stores, like MOVBstoreidx4?
* [src/cmd/compile/internal/ssa/_gen/ARM.rules:554](src/cmd/compile/internal/ssa/_gen/ARM.rules#L554): we should be able to get rid of MOVWnop all together.
* [src/cmd/compile/internal/ssa/_gen/ARM.rules:62](src/cmd/compile/internal/ssa/_gen/ARM.rules#L62): optimize this for ARMv5 and ARMv6
* [src/cmd/compile/internal/ssa/_gen/ARM64.rules:1093](src/cmd/compile/internal/ssa/_gen/ARM64.rules#L1093): we should be able to get rid of MOVDnop all together.
* [src/cmd/compile/internal/ssa/_gen/ARM64.rules:660](src/cmd/compile/internal/ssa/_gen/ARM64.rules#L660): add support for LE, GT, overflow needs to be considered.
* [src/cmd/compile/internal/ssa/_gen/LOONG64.rules:674](src/cmd/compile/internal/ssa/_gen/LOONG64.rules#L674): we should be able to get rid of MOVVnop all together.
* [src/cmd/compile/internal/ssa/_gen/LOONG64Ops.go:589](src/cmd/compile/internal/ssa/_gen/LOONG64Ops.go#L589): support register ABI on loong64
* [src/cmd/compile/internal/ssa/_gen/MIPS.rules:129](src/cmd/compile/internal/ssa/_gen/MIPS.rules#L129): optimize this case?
* [src/cmd/compile/internal/ssa/_gen/MIPS.rules:577](src/cmd/compile/internal/ssa/_gen/MIPS.rules#L577): we should be able to get rid of MOVWnop all together.
* [src/cmd/compile/internal/ssa/_gen/MIPS64.rules:686](src/cmd/compile/internal/ssa/_gen/MIPS64.rules#L686): we should be able to get rid of MOVVnop all together.
* [src/cmd/compile/internal/ssa/_gen/PPC64.rules:257](src/cmd/compile/internal/ssa/_gen/PPC64.rules#L257): optimize these cases?
* [src/cmd/compile/internal/ssa/_gen/PPC64Ops.go:568](src/cmd/compile/internal/ssa/_gen/PPC64Ops.go#L568): If vector registers are managed by regalloc
* [src/cmd/compile/internal/ssa/_gen/RISCV64.rules:503](src/cmd/compile/internal/ssa/_gen/RISCV64.rules#L503): Special handling for SP offsets, like ARM
* [src/cmd/compile/internal/ssa/_gen/RISCV64.rules:713](src/cmd/compile/internal/ssa/_gen/RISCV64.rules#L713): we should be able to get rid of MOVDnop all together.
* [src/cmd/compile/internal/ssa/_gen/S390X.rules:1161](src/cmd/compile/internal/ssa/_gen/S390X.rules#L1161): more of this
* [src/cmd/compile/internal/ssa/_gen/S390X.rules:1187](src/cmd/compile/internal/ssa/_gen/S390X.rules#L1187): more of this
* [src/cmd/compile/internal/ssa/_gen/S390X.rules:465](src/cmd/compile/internal/ssa/_gen/S390X.rules#L465): Should the optimizations be a separate pass?
* [src/cmd/compile/internal/ssa/_gen/S390X.rules:83](src/cmd/compile/internal/ssa/_gen/S390X.rules#L83): optimize these cases?
* [src/cmd/compile/internal/ssa/_gen/S390XOps.go:569](src/cmd/compile/internal/ssa/_gen/S390XOps.go#L569): have these return flags instead of bool.  The current system generates:
* [src/cmd/compile/internal/ssa/_gen/Wasm.rules:357](src/cmd/compile/internal/ssa/_gen/Wasm.rules#L357): declare these operations as commutative and get rid of these rules?
* [src/cmd/compile/internal/ssa/_gen/allocators.go:7](src/cmd/compile/internal/ssa/_gen/allocators.go#L7): should we share backing storage for similarly-shaped types?
* [src/cmd/compile/internal/ssa/_gen/genericOps.go:547](src/cmd/compile/internal/ssa/_gen/genericOps.go#L547): what's the difference between VarLive and KeepAlive?
* [src/cmd/compile/internal/ssa/_gen/main.go:28](src/cmd/compile/internal/ssa/_gen/main.go#L28): capitalize these types, so that we can more easily tell variable names
* [src/cmd/compile/internal/ssa/_gen/rulegen.go:1192](src/cmd/compile/internal/ssa/_gen/rulegen.go#L1192): when generating a constant result, use f.constVal to avoid
* [src/cmd/compile/internal/ssa/_gen/rulegen.go:885](src/cmd/compile/internal/ssa/_gen/rulegen.go#L885): pass non-nil cnt?
* [src/cmd/compile/internal/ssa/_gen/rulegen.go:956](src/cmd/compile/internal/ssa/_gen/rulegen.go#L956): does it always make sense to use the source position
* [src/cmd/compile/internal/ssa/addressingmodes.go:44](src/cmd/compile/internal/ssa/addressingmodes.go#L44): introduce auxSymOff32
* [src/cmd/compile/internal/ssa/block.go:42](src/cmd/compile/internal/ssa/block.go#L42): predecessors is a pain to maintain. Can we somehow order phi
* [src/cmd/compile/internal/ssa/check.go:125](src/cmd/compile/internal/ssa/check.go#L125): enforce types of Aux in this switch (like auxString does below)
* [src/cmd/compile/internal/ssa/check.go:278](src/cmd/compile/internal/ssa/check.go#L278): more type checks?
* [src/cmd/compile/internal/ssa/check.go:345](src/cmd/compile/internal/ssa/check.go#L345): check for cycles in values
* [src/cmd/compile/internal/ssa/compile.go:31](src/cmd/compile/internal/ssa/compile.go#L31): debugging - set flags to control verbosity of compiler,
* [src/cmd/compile/internal/ssa/compile.go:464](src/cmd/compile/internal/ssa/compile.go#L464): split required rules and optimizing rules
* [src/cmd/compile/internal/ssa/compile.go:476](src/cmd/compile/internal/ssa/compile.go#L476): split required rules and optimizing rules
* [src/cmd/compile/internal/ssa/compile.go:79](src/cmd/compile/internal/ssa/compile.go#L79): capture logging during this pass, add it to the HTML
* [src/cmd/compile/internal/ssa/config.go:389](src/cmd/compile/internal/ssa/config.go#L389): This is only used for debug printing. Maybe export config.registers?
* [src/cmd/compile/internal/ssa/config.go:81](src/cmd/compile/internal/ssa/config.go#L81): use unsafe.Pointer instead?
* [src/cmd/compile/internal/ssa/copyelim.go:94](src/cmd/compile/internal/ssa/copyelim.go#L94): Can we also simplify cases like:
* [src/cmd/compile/internal/ssa/deadcode.go:124](src/cmd/compile/internal/ssa/deadcode.go#L124): save marks only for bodies which
* [src/cmd/compile/internal/ssa/deadstore.go:15](src/cmd/compile/internal/ssa/deadstore.go#L15): use something more global.
* [src/cmd/compile/internal/ssa/debug_test.go:151](src/cmd/compile/internal/ssa/debug_test.go#L151): Technically not necessary in 1.10 and later, but it causes a largish regression that needs investigation.
* [src/cmd/compile/internal/ssa/debug_test.go:540](src/cmd/compile/internal/ssa/debug_test.go#L540): here is where variable processing will be added.  See gdbState.stepnext as a guide.
* [src/cmd/compile/internal/ssa/debug_test.go:87](src/cmd/compile/internal/ssa/debug_test.go#L87): not implemented for Delve yet, but this is the plan
* [src/cmd/compile/internal/ssa/dom.go:265](src/cmd/compile/internal/ssa/dom.go#L265): This loop is O(n^2). It used to be used in nilcheck,
* [src/cmd/compile/internal/ssa/flags_test.go:34](src/cmd/compile/internal/ssa/flags_test.go#L34): can we cover all outputs?
* [src/cmd/compile/internal/ssa/flags_test.go:56](src/cmd/compile/internal/ssa/flags_test.go#L56): can we cover all outputs?
* [src/cmd/compile/internal/ssa/func_test.go:155](src/cmd/compile/internal/ssa/func_test.go#L155): Either mark some SSA tests as t.Parallel,
* [src/cmd/compile/internal/ssa/fuse.go:77](src/cmd/compile/internal/ssa/fuse.go#L77): If ss doesn't contain any OpPhis, are s0 and s1 dead code anyway.
* [src/cmd/compile/internal/ssa/fuse_branchredirect.go:40](src/cmd/compile/internal/ssa/fuse_branchredirect.go#L40): if b contains only OpCopy or OpNot related to b.Controls,
* [src/cmd/compile/internal/ssa/fuse_comparisons.go:90](src/cmd/compile/internal/ssa/fuse_comparisons.go#L90): could negate condition(s) to merge controls.
* [src/cmd/compile/internal/ssa/html.go:1013](src/cmd/compile/internal/ssa/html.go#L1013): Using the value ID as the class ignores the fact
* [src/cmd/compile/internal/ssa/html.go:1021](src/cmd/compile/internal/ssa/html.go#L1021): improve this for HTML?
* [src/cmd/compile/internal/ssa/html.go:1062](src/cmd/compile/internal/ssa/html.go#L1062): HTML, not text, <br> for line breaks, etc.
* [src/cmd/compile/internal/ssa/html.go:599](src/cmd/compile/internal/ssa/html.go#L599): Implement smarter auto-zoom using the viewBox attribute
* [src/cmd/compile/internal/ssa/html.go:638](src/cmd/compile/internal/ssa/html.go#L638): scale the graph with the viewBox attribute.
* [src/cmd/compile/internal/ssa/html.go:961](src/cmd/compile/internal/ssa/html.go#L961): Using the value ID as the class ignores the fact
* [src/cmd/compile/internal/ssa/html.go:969](src/cmd/compile/internal/ssa/html.go#L969): Any intra-value formatting?
* [src/cmd/compile/internal/ssa/layout.go:140](src/cmd/compile/internal/ssa/layout.go#L140): improve this part
* [src/cmd/compile/internal/ssa/layout.go:173](src/cmd/compile/internal/ssa/layout.go#L173): Order these to minimize jump distances?
* [src/cmd/compile/internal/ssa/loopbce.go:133](src/cmd/compile/internal/ssa/loopbce.go#L133): Could be extended to include disjointed loop headers.
* [src/cmd/compile/internal/ssa/loopbce.go:307](src/cmd/compile/internal/ssa/loopbce.go#L307): other unrolling idioms
* [src/cmd/compile/internal/ssa/loopbce.go:99](src/cmd/compile/internal/ssa/loopbce.go#L99): Handle unsigned comparisons?
* [src/cmd/compile/internal/ssa/loopreschedchecks.go:359](src/cmd/compile/internal/ssa/loopreschedchecks.go#L359): convert to explicit stack from recursion.
* [src/cmd/compile/internal/ssa/loopreschedchecks.go:401](src/cmd/compile/internal/ssa/loopreschedchecks.go#L401): convert to explicit stack from recursion.
* [src/cmd/compile/internal/ssa/loopreschedchecks.go:45](src/cmd/compile/internal/ssa/loopreschedchecks.go#L45): when split information is recorded in export data, insert checks only on backedges that can be reached on a split-call-free path.
* [src/cmd/compile/internal/ssa/loopreschedchecks.go:89](src/cmd/compile/internal/ssa/loopreschedchecks.go#L89): could filter here by calls in loops, if declared and inferred nosplit are recorded in export data.
* [src/cmd/compile/internal/ssa/memcombine.go:504](src/cmd/compile/internal/ssa/memcombine.go#L504): the constant source and consecutive load source cases
* [src/cmd/compile/internal/ssa/nilcheck.go:21](src/cmd/compile/internal/ssa/nilcheck.go#L21): Eliminate more nil checks.
* [src/cmd/compile/internal/ssa/nilcheck.go:334](src/cmd/compile/internal/ssa/nilcheck.go#L334): if b.Kind == BlockPlain, start the analysis in the subsequent block to find
* [src/cmd/compile/internal/ssa/op.go:122](src/cmd/compile/internal/ssa/op.go#L122): there is a Clever Hack that allows pre-generation of a small-ish number of the slices
* [src/cmd/compile/internal/ssa/phiopt.go:170](src/cmd/compile/internal/ssa/phiopt.go#L170): handle more than 2 predecessors, e.g. a || b || c.
* [src/cmd/compile/internal/ssa/phiopt.go:176](src/cmd/compile/internal/ssa/phiopt.go#L176): v = OpPhi (ConstBool [true]) (Arg <bool> {value})
* [src/cmd/compile/internal/ssa/phiopt.go:32](src/cmd/compile/internal/ssa/phiopt.go#L32): handle more than 2 predecessors, e.g. a || b || c.
* [src/cmd/compile/internal/ssa/prove.go:1370](src/cmd/compile/internal/ssa/prove.go#L1370): if both start and end are constants we should rewrite such that the comparison
* [src/cmd/compile/internal/ssa/prove.go:1590](src/cmd/compile/internal/ssa/prove.go#L1590): others?
* [src/cmd/compile/internal/ssa/prove.go:1687](src/cmd/compile/internal/ssa/prove.go#L1687): boolean?
* [src/cmd/compile/internal/ssa/prove.go:1753](src/cmd/compile/internal/ssa/prove.go#L1753): if y.umax and y.umin share a leading bit pattern, y also has that leading bit pattern.
* [src/cmd/compile/internal/ssa/prove.go:1850](src/cmd/compile/internal/ssa/prove.go#L1850): we could handle signed limits but I didn't bother.
* [src/cmd/compile/internal/ssa/prove.go:1863](src/cmd/compile/internal/ssa/prove.go#L1863): we could handle signed limits but I didn't bother.
* [src/cmd/compile/internal/ssa/prove.go:1915](src/cmd/compile/internal/ssa/prove.go#L1915): how about p->yes->b->yes, i.e. a loop in yes.
* [src/cmd/compile/internal/ssa/prove.go:1923](src/cmd/compile/internal/ssa/prove.go#L1923): this loop can lead to quadratic behavior, as
* [src/cmd/compile/internal/ssa/prove.go:2025](src/cmd/compile/internal/ssa/prove.go#L2025): investigate how to always add facts without much slowdown, see issue #57959
* [src/cmd/compile/internal/ssa/prove.go:2228](src/cmd/compile/internal/ssa/prove.go#L2228): add other architectures?
* [src/cmd/compile/internal/ssa/prove.go:2356](src/cmd/compile/internal/ssa/prove.go#L2356): figure out how to remove an entry from a jump table
* [src/cmd/compile/internal/ssa/prove.go:437](src/cmd/compile/internal/ssa/prove.go#L437): check if there are cases that matter where we have
* [src/cmd/compile/internal/ssa/prove.go:566](src/cmd/compile/internal/ssa/prove.go#L566): check
* [src/cmd/compile/internal/ssa/prove.go:579](src/cmd/compile/internal/ssa/prove.go#L579): pos is probably wrong. This is the position where v is defined,
* [src/cmd/compile/internal/ssa/prove.go:692](src/cmd/compile/internal/ssa/prove.go#L692): v.Block is wrong?
* [src/cmd/compile/internal/ssa/prove.go:728](src/cmd/compile/internal/ssa/prove.go#L728): v.Block is wrong here
* [src/cmd/compile/internal/ssa/prove.go:816](src/cmd/compile/internal/ssa/prove.go#L816): this does not do transitive equality.
* [src/cmd/compile/internal/ssa/prove.go:969](src/cmd/compile/internal/ssa/prove.go#L969): Since prove now derives transitive relations, it
* [src/cmd/compile/internal/ssa/regalloc.go:1062](src/cmd/compile/internal/ssa/regalloc.go#L1062): Improve this part. At least the size of endRegs of the predecessor also has
* [src/cmd/compile/internal/ssa/regalloc.go:1083](src/cmd/compile/internal/ssa/regalloc.go#L1083): improve the prediction of the likely predecessor. The following
* [src/cmd/compile/internal/ssa/regalloc.go:1111](src/cmd/compile/internal/ssa/regalloc.go#L1111): pick best of (already processed) predecessors?
* [src/cmd/compile/internal/ssa/regalloc.go:112](src/cmd/compile/internal/ssa/regalloc.go#L112): maybe we should introduce these extra phis?
* [src/cmd/compile/internal/ssa/regalloc.go:1289](src/cmd/compile/internal/ssa/regalloc.go#L1289): prioritize likely successor?
* [src/cmd/compile/internal/ssa/regalloc.go:166](src/cmd/compile/internal/ssa/regalloc.go#L166): regMask -> regSet?
* [src/cmd/compile/internal/ssa/regalloc.go:1861](src/cmd/compile/internal/ssa/regalloc.go#L1861): sort by distance, pick the closest ones?
* [src/cmd/compile/internal/ssa/regalloc.go:2064](src/cmd/compile/internal/ssa/regalloc.go#L2064): find a way to make this O(1) without arbitrary cutoffs.
* [src/cmd/compile/internal/ssa/regalloc.go:2601](src/cmd/compile/internal/ssa/regalloc.go#L2601): reuse these slots. They'll need to be erased first.
* [src/cmd/compile/internal/ssa/regalloc.go:2652](src/cmd/compile/internal/ssa/regalloc.go#L2652): this could be quadratic if lots of variables are live across lots of
* [src/cmd/compile/internal/ssa/regalloc.go:2672](src/cmd/compile/internal/ssa/regalloc.go#L2672): Do a better job yet. Here's one possibility:
* [src/cmd/compile/internal/ssa/regalloc.go:2729](src/cmd/compile/internal/ssa/regalloc.go#L2729): if v is a phi, save desired register for phi inputs.
* [src/cmd/compile/internal/ssa/regalloc.go:441](src/cmd/compile/internal/ssa/regalloc.go#L441): Prefer registers with already spilled Values?
* [src/cmd/compile/internal/ssa/regalloc.go:442](src/cmd/compile/internal/ssa/regalloc.go#L442): Modify preference using affinity graph.
* [src/cmd/compile/internal/ssa/regalloc.go:443](src/cmd/compile/internal/ssa/regalloc.go#L443): if a single value is in multiple registers, spill one of them
* [src/cmd/compile/internal/ssa/regalloc.go:784](src/cmd/compile/internal/ssa/regalloc.go#L784): honor GOCLOBBERDEADHASH, or maybe GOSSAHASH.
* [src/cmd/compile/internal/ssa/regalloc_test.go:205](src/cmd/compile/internal/ssa/regalloc_test.go#L205): resurrect moving spills out of loops? We could put spills at the start of both exit1 and exit2.
* [src/cmd/compile/internal/ssa/rewrite.go:1166](src/cmd/compile/internal/ssa/rewrite.go#L1166): all.bash runs compilers in parallel. Need to synchronize logging somehow?
* [src/cmd/compile/internal/ssa/rewrite.go:125](src/cmd/compile/internal/ssa/rewrite.go#L125): it's possible (in FOR loops, in particular) for statement boundaries for the same
* [src/cmd/compile/internal/ssa/rewrite.go:1369](src/cmd/compile/internal/ssa/rewrite.go#L1369): expand this check to allow other architectures
* [src/cmd/compile/internal/ssa/rewrite.go:2342](src/cmd/compile/internal/ssa/rewrite.go#L2342): return true if !v.Type.IsSigned()
* [src/cmd/compile/internal/ssa/rewrite.go:746](src/cmd/compile/internal/ssa/rewrite.go#L746): kind of a hack - allows nil interface through
* [src/cmd/compile/internal/ssa/shortcircuit.go:473](src/cmd/compile/internal/ssa/shortcircuit.go#L473): handle more cases; shortcircuit optimizations turn out to be reasonably high impact
* [src/cmd/compile/internal/ssa/stackalloc.go:300](src/cmd/compile/internal/ssa/stackalloc.go#L300): this could be quadratic if lots of variables are live across lots of
* [src/cmd/compile/internal/ssa/stackalloc.go:5](src/cmd/compile/internal/ssa/stackalloc.go#L5): live at start of block instead?
* [src/cmd/compile/internal/ssa/value.go:602](src/cmd/compile/internal/ssa/value.go#L602): allow if all indexes are constant.
* [src/cmd/compile/internal/ssagen/pgen.go:157](src/cmd/compile/internal/ssagen/pgen.go#L157): maybe do this for PAUTO as well?
* [src/cmd/compile/internal/ssagen/phi.go:124](src/cmd/compile/internal/ssagen/phi.go#L124): encode defvars some other way (explicit ops)? make defvars[n] a slice instead of a map.
* [src/cmd/compile/internal/ssagen/phi.go:246](src/cmd/compile/internal/ssagen/phi.go#L246): if the variable is dead at c, skip it.
* [src/cmd/compile/internal/ssagen/phi.go:256](src/cmd/compile/internal/ssagen/phi.go#L256): line number right?
* [src/cmd/compile/internal/ssagen/phi.go:414](src/cmd/compile/internal/ssagen/phi.go#L414): stop walking the iterated domininance frontier when
* [src/cmd/compile/internal/ssagen/phi.go:41](src/cmd/compile/internal/ssagen/phi.go#L41): make this part of cmd/compile/internal/ssa somehow?
* [src/cmd/compile/internal/ssagen/phi.go:420](src/cmd/compile/internal/ssagen/phi.go#L420): move this file to ../ssa, then use sparseSet there.
* [src/cmd/compile/internal/ssagen/ssa.go:1496](src/cmd/compile/internal/ssagen/ssa.go#L1496): never rewrite OPANIC to OCALLFUNC in the
* [src/cmd/compile/internal/ssagen/ssa.go:1720](src/cmd/compile/internal/ssagen/ssa.go#L1720): detect defaults for len/cap also.
* [src/cmd/compile/internal/ssagen/ssa.go:1988](src/cmd/compile/internal/ssagen/ssa.go#L1988): assumes missing the table entirely is unlikely. True?
* [src/cmd/compile/internal/ssagen/ssa.go:2138](src/cmd/compile/internal/ssagen/ssa.go#L2138): check that throwing away the nilcheck result is ok.
* [src/cmd/compile/internal/ssagen/ssa.go:3869](src/cmd/compile/internal/ssagen/ssa.go#L3869): have the frontend give us branch prediction hints for
* [src/cmd/compile/internal/ssagen/ssa.go:395](src/cmd/compile/internal/ssagen/ssa.go#L395): generate and print a mapping from nodes to values and blocks
* [src/cmd/compile/internal/ssagen/ssa.go:3962](src/cmd/compile/internal/ssagen/ssa.go#L3962): do we need to update named values here?
* [src/cmd/compile/internal/ssagen/ssa.go:4149](src/cmd/compile/internal/ssagen/ssa.go#L4149): do not emit sfcall if operation can be optimized to constant in later
* [src/cmd/compile/internal/ssagen/ssa.go:441](src/cmd/compile/internal/ssagen/ssa.go#L441): use generic pointer type (unsafe.Pointer?) instead
* [src/cmd/compile/internal/ssagen/ssa.go:4671](src/cmd/compile/internal/ssagen/ssa.go#L4671): Make OpAddr use AuxInt as well as Aux.
* [src/cmd/compile/internal/ssagen/ssa.go:4805](src/cmd/compile/internal/ssagen/ssa.go#L4805): handle this case? Named return values must be
* [src/cmd/compile/internal/ssagen/ssa.go:4819](src/cmd/compile/internal/ssagen/ssa.go#L4819): try to make more variables SSAable?
* [src/cmd/compile/internal/ssagen/ssa.go:5049](src/cmd/compile/internal/ssagen/ssa.go#L5049): if the writebarrier pass knows how to reorder stores,
* [src/cmd/compile/internal/ssagen/ssa.go:5906](src/cmd/compile/internal/ssagen/ssa.go#L5906): get rid of some of these temporaries.
* [src/cmd/compile/internal/ssagen/ssa.go:6041](src/cmd/compile/internal/ssagen/ssa.go#L6041): allow this.
* [src/cmd/compile/internal/ssagen/ssa.go:6607](src/cmd/compile/internal/ssagen/ssa.go#L6607): are there others?
* [src/cmd/compile/internal/ssagen/ssa.go:7134](src/cmd/compile/internal/ssagen/ssa.go#L7134): .Equal() instead?
* [src/cmd/compile/internal/ssagen/ssa.go:7274](src/cmd/compile/internal/ssagen/ssa.go#L7274): keep the result of this function somewhere in the ODOT Node
* [src/cmd/compile/internal/ssagen/ssa.go:840](src/cmd/compile/internal/ssagen/ssa.go#L840): could also seek minimum position?
* [src/cmd/compile/internal/ssagen/ssa.go:886](src/cmd/compile/internal/ssagen/ssa.go#L886): keep a single varnum map, then make all of these maps slices instead?
* [src/cmd/compile/internal/staticinit/sched.go:1023](src/cmd/compile/internal/staticinit/sched.go#L1023): handle more operations, see details discussion in go.dev/cl/466277.
* [src/cmd/compile/internal/staticinit/sched.go:929](src/cmd/compile/internal/staticinit/sched.go#L929): Should ir.OuterValue handle this?
* [src/cmd/compile/internal/test/pgo_inl_test.go:91](src/cmd/compile/internal/test/pgo_inl_test.go#L91): maybe adjust the test to work with default threshold.
* [src/cmd/compile/internal/test/testdata/gen/arithBoundaryGen.go:146](src/cmd/compile/internal/test/testdata/gen/arithBoundaryGen.go#L146): clean up this duplication
* [src/cmd/compile/internal/test/testdata/gen/cmpConstGen.go:190](src/cmd/compile/internal/test/testdata/gen/cmpConstGen.go#L190): could also test constant on lhs.
* [src/cmd/compile/internal/types2/api_test.go:2039](src/cmd/compile/internal/types2/api_test.go#L2039): add more tests for complex types.
* [src/cmd/compile/internal/types2/scope.go:79](src/cmd/compile/internal/types2/scope.go#L79): remove this once gotypesalias=0 is no longer supported.
* [src/cmd/compile/internal/walk/assign.go:712](src/cmd/compile/internal/walk/assign.go#L712): &s[s.len] - hn?
* [src/cmd/compile/internal/walk/complit.go:196](src/cmd/compile/internal/walk/complit.go#L196): expand documentation.
* [src/cmd/compile/internal/walk/convert.go:209](src/cmd/compile/internal/walk/convert.go#L209): never happens because pointers are directIface?
* [src/cmd/compile/internal/walk/expr.go:1010](src/cmd/compile/internal/walk/expr.go#L1010): is there a better way than hardcoding the names?
* [src/cmd/compile/internal/walk/expr.go:685](src/cmd/compile/internal/walk/expr.go#L685): Remove this code once we can introduce
* [src/cmd/compile/internal/walk/order.go:229](src/cmd/compile/internal/walk/order.go#L229): expand this to all static composite literal nodes?
* [src/cmd/compile/internal/walk/switch.go:565](src/cmd/compile/internal/walk/switch.go#L565): add len(newCases) case, mark switch as bounded
* [src/cmd/compile/internal/walk/switch.go:946](src/cmd/compile/internal/walk/switch.go#L946): what if the best split is still pretty bad?
* [src/cmd/compile/internal/walk/switch.go:976](src/cmd/compile/internal/walk/switch.go#L976): if expr[bestIdx] has enough different possible values, use a jump table.
* [src/cmd/compile/internal/wasm/ssa.go:306](src/cmd/compile/internal/wasm/ssa.go#L306): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/compile/internal/x86/ssa.go:660](src/cmd/compile/internal/x86/ssa.go#L660): use MOVLreg for reg->reg copies instead of OpCopy?
* [src/cmd/compile/internal/x86/ssa.go:817](src/cmd/compile/internal/x86/ssa.go#L817): We currently use the 2-byte instruction TESTB AX, (reg).
* [src/cmd/compile/internal/x86/ssa.go:913](src/cmd/compile/internal/x86/ssa.go#L913): implement for clobberdead experiment. Nop is ok for now.
* [src/cmd/cover/cover.go:589](src/cmd/cover/cover.go#L589): process files in parallel here if it matters.
* [src/cmd/cover/cover.go:753](src/cmd/cover/cover.go#L753): Nested simple blocks get unnecessary (but correct) counters
* [src/cmd/cover/cover.go:823](src/cmd/cover/cover.go#L823): what if there's more than one? Probably doesn't matter much.
* [src/cmd/cover/cover.go:895](src/cmd/cover/cover.go#L895): what if there's more than one? Probably doesn't matter much.
* [src/cmd/doc/pkg.go:1048](src/cmd/doc/pkg.go#L1048): Anonymous methods (embedding)
* [src/cmd/doc/pkg.go:1095](src/cmd/doc/pkg.go#L1095): Anonymous fields.
* [src/cmd/doc/pkg.go:171](src/cmd/doc/pkg.go#L171): go/doc does not include typed constants in the constants
* [src/cmd/doc/pkg.go:687](src/cmd/doc/pkg.go#L687): Provide access to TODOs and NOTEs as well (very noisy so off by default)?
* [src/cmd/doc/pkg.go:790](src/cmd/doc/pkg.go#L790): Should we elide unexported symbols from a single spec?
* [src/cmd/doc/pkg.go:792](src/cmd/doc/pkg.go#L792): Would be nice if go/doc did this for us.
* [src/cmd/fix/typecheck.go:717](src/cmd/fix/typecheck.go#L717): more cases. This is enough for the cftype fix.
* [src/cmd/go/go_test.go:2142](src/cmd/go/go_test.go#L2142): deduplicate this struct from cmd/link/internal/ld/pe.go
* [src/cmd/go/internal/clean/clean.go:233](src/cmd/go/internal/clean/clean.go#L233): These are dregs left by Makefile-based builds.
* [src/cmd/go/internal/clean/clean.go:345](src/cmd/go/internal/clean/clean.go#L345): Remove once Makefiles are forgotten.
* [src/cmd/go/internal/list/list.go:735](src/cmd/go/internal/list/list.go#L735): Use pkgsFilter?
* [src/cmd/go/internal/load/pkg.go:1938](src/cmd/go/internal/load/pkg.go#L1938): The .swig and .swigcxx files can use
* [src/cmd/go/internal/load/pkg.go:2406](src/cmd/go/internal/load/pkg.go#L2406): since we control cmd/link, in theory we can parse ldflags to
* [src/cmd/go/internal/modfetch/codehost/codehost.go:372](src/cmd/go/internal/modfetch/codehost/codehost.go#L372): Impose limits on command output size.
* [src/cmd/go/internal/modfetch/codehost/codehost.go:373](src/cmd/go/internal/modfetch/codehost/codehost.go#L373): Set environment to get English error messages.
* [src/cmd/go/internal/modfetch/codehost/git.go:690](src/cmd/go/internal/modfetch/codehost/git.go#L690): Could use git cat-file --batch.
* [src/cmd/go/internal/modfetch/codehost/git.go:859](src/cmd/go/internal/modfetch/codehost/git.go#L859): Use maxSize or drop it.
* [src/cmd/go/internal/modfetch/codehost/git_test.go:45](src/cmd/go/internal/modfetch/codehost/git_test.go#L45): Convert gitrepo1 to svn, bzr, fossil and add tests.
* [src/cmd/go/internal/modfetch/coderepo.go:443](src/cmd/go/internal/modfetch/coderepo.go#L443): It would be nice to return an error like "not a module".
* [src/cmd/go/internal/modload/load.go:2195](src/cmd/go/internal/modload/load.go#L2195): Is this check needed?
* [src/cmd/go/internal/work/exec.go:2760](src/cmd/go/internal/work/exec.go#L2760): CGO_FLAGS?
* [src/cmd/go/internal/work/exec.go:2769](src/cmd/go/internal/work/exec.go#L2769): make cgo not depend on $GOARCH?
* [src/cmd/go/internal/work/exec.go:3104](src/cmd/go/internal/work/exec.go#L3104): Don't build a shared library, once SWIG emits the necessary
* [src/cmd/go/internal/work/exec.go:3427](src/cmd/go/internal/work/exec.go#L3427): Note that other toolchains like CC are missing here for now.
* [src/cmd/go/internal/work/gc.go:198](src/cmd/go/internal/work/gc.go#L198): Test and delete these conditions.
* [src/cmd/go/internal/work/shell.go:440](src/cmd/go/internal/work/shell.go#L440): This is what we've done for a long time, but it may be a
* [src/cmd/go/internal/work/shell.go:674](src/cmd/go/internal/work/shell.go#L674): See issue 5279. The printing of commands needs a complete redo.
* [src/cmd/go/testdata/script/fipssnap.txt:26](src/cmd/go/testdata/script/fipssnap.txt#L26): enable when we add inprocess.txt
* [src/cmd/go/testdata/script/gccgo_link_ldflags.txt:12](src/cmd/go/testdata/script/gccgo_link_ldflags.txt#L12): remove once gccgo on builder is updated
* [src/cmd/go/testdata/script/mod_get_patchcycle.txt:9](src/cmd/go/testdata/script/mod_get_patchcycle.txt#L9): A mention of b v0.1.0 would be nice.
* [src/cmd/go/testdata/script/mod_list_bad_import.txt:57](src/cmd/go/testdata/script/mod_list_bad_import.txt#L57): go list creates a dummy package with the import-not-found
* [src/cmd/go/testdata/script/mod_tidy_convergence.txt:46](src/cmd/go/testdata/script/mod_tidy_convergence.txt#L46): This error message should be clearer — it doesn't indicate why v0.2.0-pre is required.
* [src/cmd/go/testdata/script/mod_tidy_convergence.txt:67](src/cmd/go/testdata/script/mod_tidy_convergence.txt#L67): This error message should be clearer — it doesn't indicate why v0.2.0-pre is required.
* [src/cmd/go/testdata/script/mod_tidy_convergence_loop.txt:53](src/cmd/go/testdata/script/mod_tidy_convergence_loop.txt#L53): These error messages should be clearer — it doesn't indicate why v0.2.0-pre is required.
* [src/runtime/os_plan9.go:531](src/runtime/os_plan9.go#L531): Use a note like we use signals on POSIX OSes
* [src/runtime/os_wasm.go:140](src/runtime/os_wasm.go#L140): Make this a compiler intrinsic
* [src/runtime/os_windows.go:795](src/runtime/os_windows.go#L795): this is completely broken. The args passed to newosproc0 (in asm_amd64.s)
* [src/runtime/panic.go:379](src/runtime/panic.go#L379): We could arrange for the compiler to call into the
* [src/runtime/panic.go:61](src/runtime/panic.go#L61): is this redundant? How could we be in malloc
* [src/runtime/pprof/label_test.go:187](src/runtime/pprof/label_test.go#L187): hit slow path in Labels
* [src/runtime/pprof/proto.go:197](src/runtime/pprof/proto.go#L197): we set HasFunctions if all symbols from samples were symbolized (hasFuncs).
* [src/runtime/pprof/proto.go:386](src/runtime/pprof/proto.go#L386): Anything for tagProfile_DropFrames?
* [src/runtime/pprof/proto.go:387](src/runtime/pprof/proto.go#L387): Anything for tagProfile_KeepFrames?
* [src/runtime/pprof/proto.go:740](src/runtime/pprof/proto.go#L740): pprof's remapMappingIDs makes one adjustment:
* [src/runtime/preempt.go:129](src/runtime/preempt.go#L129): It would be nicer if we could
* [src/runtime/preempt.go:181](src/runtime/preempt.go#L181): It would be much better if we didn't
* [src/runtime/preempt.go:237](src/runtime/preempt.go#L237): Don't busy wait. This loop should really only
* [src/runtime/preempt.go:409](src/runtime/preempt.go#L409): Empirically we still need the fd == nil check. Why?
* [src/runtime/preempt.go:411](src/runtime/preempt.go#L411): Are there cases that are safe but don't have a
* [src/runtime/proc.go:2782](src/runtime/proc.go#L2782): This may be unnecessary on Windows, which
* [src/runtime/proc.go:3051](src/runtime/proc.go#L3051): fast atomic
* [src/runtime/race.go:309](src/runtime/race.go#L309): Does this need to handle malloc headers?
* [src/runtime/race/testdata/waitgroup_test.go:224](src/runtime/race/testdata/waitgroup_test.go#L224): this is actually a panic-synchronization test, not a
* [src/runtime/race_ppc64le.s:405](src/runtime/race_ppc64le.s#L405): What's this supposed to be?
* [src/runtime/rt0_android_386.s:24](src/runtime/rt0_android_386.s#L24): wire up necessary VDSO (see os_linux_386.go)
* [src/runtime/runtime-gdb.py:714](src/runtime/runtime-gdb.py#L714): print interface's methods and dynamic type's func pointers thereof.
* [src/runtime/runtime1.go:101](src/runtime/runtime1.go#L101): These should be locals in testAtomic64, but we don't 8-byte
* [src/runtime/runtime2.go:431](src/runtime/runtime2.go#L431): fold in to atomicstatus
* [src/runtime/runtime2.go:721](src/runtime/runtime2.go#L721): Consider caching this in the running G.
* [src/runtime/security_test.go:144](src/runtime/security_test.go#L144): check the registers aren't leaked?
* [src/runtime/signal_unix.go:1465](src/runtime/signal_unix.go#L1465): emulate si_addr
* [src/runtime/signal_unix.go:406](src/runtime/signal_unix.go#L406): in efence mode, stack is sysAlloc'd, so this wouldn't
* [src/runtime/signal_unix.go:462](src/runtime/signal_unix.go#L462): reuse the current m here by using the gsignal and adjustSignalStack,
* [src/runtime/signal_windows.go:165](src/runtime/signal_windows.go#L165): revisit this workaround if/when closures
* [src/runtime/signal_windows_test.go:119](src/runtime/signal_windows_test.go#L119): remove when windows/arm64 and windows/arm support SEH stack unwinding.
* [src/runtime/slice.go:386](src/runtime/slice.go#L386): is this still worth it with new memmove impl?
* [src/runtime/softfloat64.go:515](src/runtime/softfloat64.go#L515): are there double-rounding problems here? See issue 48807.
* [src/runtime/stack.go:968](src/runtime/stack.go#L968): double check all gp. shouldn't be getg().
* [src/runtime/stubs_386.go:23](src/runtime/stubs_386.go#L23): Make this a compiler intrinsic
* [src/runtime/stubs_amd64.go:55](src/runtime/stubs_amd64.go#L55): Make this a compiler intrinsic
* [src/runtime/stubs_arm.go:28](src/runtime/stubs_arm.go#L28): Make this a compiler intrinsic
* [src/runtime/stubs_arm64.go:26](src/runtime/stubs_arm64.go#L26): Make this a compiler intrinsic
* [src/runtime/stubs_loong64.go:21](src/runtime/stubs_loong64.go#L21): Make this a compiler intrinsic
* [src/runtime/stubs_mips64x.go:19](src/runtime/stubs_mips64x.go#L19): Make this a compiler intrinsic
* [src/runtime/stubs_mipsx.go:14](src/runtime/stubs_mipsx.go#L14): Make this a compiler intrinsic
* [src/runtime/stubs_ppc64x.go:25](src/runtime/stubs_ppc64x.go#L25): Make this a compiler intrinsic
* [src/runtime/stubs_riscv64.go:24](src/runtime/stubs_riscv64.go#L24): Make this a compiler intrinsic
* [src/runtime/stubs_s390x.go:12](src/runtime/stubs_s390x.go#L12): Make this a compiler intrinsic
* [src/runtime/symtab.go:254](src/runtime/symtab.go#L254): It would be more efficient to report only physical PCs to pprof and
* [src/runtime/symtab.go:740](src/runtime/symtab.go#L740): Perhaps we should report no function at all in that case.
* [src/runtime/symtab.go:885](src/runtime/symtab.go#L885): are datap.text and datap.minpc always equal?
* [src/runtime/symtabinl_test.go:47](src/runtime/symtabinl_test.go#L47): If we ever have function end information, use that to make
* [src/runtime/sys_freebsd_arm.s:405](src/runtime/sys_freebsd_arm.s#L405): this is only valid for ARMv7+
* [src/runtime/sys_linux_arm64.s:705](src/runtime/sys_linux_arm64.s#L705): setup TLS.
* [src/runtime/sys_linux_loong64.s:591](src/runtime/sys_linux_loong64.s#L591): setup TLS.
* [src/runtime/sys_linux_mips64x.s:524](src/runtime/sys_linux_mips64x.s#L524): setup TLS.
* [src/runtime/sys_linux_ppc64x.s:477](src/runtime/sys_linux_ppc64x.s#L477): Indirectly call runtime.sigtrampgo to avoid the linker's static NOSPLIT stack
* [src/runtime/sys_linux_ppc64x.s:699](src/runtime/sys_linux_ppc64x.s#L699): setup TLS.
* [src/runtime/sys_netbsd_arm.s:413](src/runtime/sys_netbsd_arm.s#L413): this is only valid for ARMv7+
* [src/runtime/sys_windows_386.s:270](src/runtime/sys_windows_386.s#L270): don't use the arbitrary pointer (see go.dev/issue/59824)
* [src/runtime/sys_windows_amd64.s:314](src/runtime/sys_windows_amd64.s#L314): don't use the arbitrary pointer (see go.dev/issue/59824)
* [src/runtime/sys_windows_arm64.s:253](src/runtime/sys_windows_arm64.s#L253): don't use the arbitrary pointer (see go.dev/issue/59824)
* [src/runtime/syscall_aix.go:58](src/runtime/syscall_aix.go#L58): remove r2 from zsyscall_aix_$GOARCH.go
* [src/runtime/testdata/testwinlib/main.c:26](src/runtime/testdata/testwinlib/main.c#L26): remove when windows/arm64 supports SEH stack unwinding.
* [src/runtime/traceback.go:1045](src/runtime/traceback.go#L1045): Unify this with gentraceback and CallersFrames.
* [src/runtime/traceback.go:627](src/runtime/traceback.go#L627): Why does &u.cache cause u to escape? (Same in traceback2)
* [src/runtime/traceback.go:65](src/runtime/traceback.go#L65): Distinguish frame.continpc, which is really the stack map PC, from
* [src/runtime/tracecpu.go:263](src/runtime/tracecpu.go#L263): Is it safe to osyield here? https://go.dev/issue/52672
* [src/runtime/type.go:103](src/runtime/type.go#L103): we could use &t.GCData as the slot, but types are
* [src/slices/slices.go:428](src/slices/slices.go#L428): There are other rotate algorithms.
* [src/slices/slices.go:452](src/slices/slices.go#L452): use a runtime/unsafe facility once one becomes available. See issue 12445.
* [src/slices/slices.go:467](src/slices/slices.go#L467): what if the overlap is by a non-integral number of Es?
* [src/strconv/ftoa.go:15](src/strconv/ftoa.go#L15): move elsewhere?
* [src/strconv/quote.go:513](src/strconv/quote.go#L513): IsPrint is a local implementation of unicode.IsPrint, verified by the tests
* [src/strings/builder.go:31](src/strings/builder.go#L31): once issue 7921 is fixed, this should be reverted to
* [src/strings/strings.go:835](src/strings/strings.go#L835): update when package unicode captures more of the properties.
* [src/syscall/mksyscall.pl:398](src/syscall/mksyscall.pl#L398): this assumes tags are just simply comma separated. For now this is all the uses.
* [src/syscall/mksyscall_libc.pl:306](src/syscall/mksyscall_libc.pl#L306): this assumes tags are just simply comma separated. For now this is all the uses.
* [src/syscall/tables_js.go:102](src/syscall/tables_js.go#L102): Auto-generate some day. (Hard-coded in binaries so not likely to change.)
* [src/syscall/tables_js.go:15](src/syscall/tables_js.go#L15): delete? replace with something meaningful?
* [src/syscall/tables_js.go:230](src/syscall/tables_js.go#L230): Auto-generate some day. (Hard-coded in binaries so not likely to change.)
* [src/syscall/tables_wasip1.go:11](src/syscall/tables_wasip1.go#L11): Auto-generate some day. (Hard-coded in binaries so not likely to change.)
* [src/syscall/tables_wasip1.go:94](src/syscall/tables_wasip1.go#L94): Auto-generate some day. (Hard-coded in binaries so not likely to change.)
* [src/syscall/zsyscall_windows.go:32](src/syscall/zsyscall_windows.go#L32): add more here, after collecting data on the common
* [src/testing/match.go:47](src/testing/match.go#L47): fix test_main to avoid race and improve caching, also allowing to
* [src/testing/testing.go:2448](src/testing/testing.go#L2448): Worth doing better? Probably not, because we're here only
* [src/testing/testing_windows.go:40](src/testing/testing_windows.go#L40): If Windows runtime implements high resolution timing then highPrecisionTime
* [src/text/template/exec.go:114](src/text/template/exec.go#L114): It would be nice if ExecError was more broken down, but
* [src/text/template/funcs.go:38](src/text/template/funcs.go#L38): revert this back to a global map once golang.org/issue/2559 is fixed.
* [src/text/template/funcs.go:408](src/text/template/funcs.go#L408): Perhaps allow comparison between signed and unsigned integers.
* [src/text/template/funcs.go:71](src/text/template/funcs.go#L71): revert this back to a global map once golang.org/issue/2559 is fixed.
* [src/text/template/parse/node.go:360](src/text/template/parse/node.go#L360): fix one day?
* [src/text/template/parse/node.go:368](src/text/template/parse/node.go#L368): fix one day?
* [src/text/template/parse/node.go:439](src/text/template/parse/node.go#L439): Not really a problem; could change API without effect but
* [src/text/template/parse/node.go:473](src/text/template/parse/node.go#L473): Not really a problem; could change API without effect but
* [src/unicode/casetables.go:5](src/unicode/casetables.go#L5): This file contains the special casing rules for Turkish and Azeri only.
* [src/vendor/golang.org/x/crypto/chacha20/xor.go:23](src/vendor/golang.org/x/crypto/chacha20/xor.go#L23): delete once the compiler does a reliably
* [src/vendor/golang.org/x/net/http/httpguts/httplex.go:117](src/vendor/golang.org/x/net/http/httpguts/httplex.go#L117): consider using strings.Trim(x, " \t") instead,
* [src/vendor/golang.org/x/net/http/httpproxy/proxy.go:297](src/vendor/golang.org/x/net/http/httpproxy/proxy.go#L297): Consider removing this check after verifying performance is okay.
* [src/vendor/golang.org/x/net/http2/hpack/hpack.go:146](src/vendor/golang.org/x/net/http2/hpack/hpack.go#L146): add method *Decoder.Reset(maxSize, emitFunc) to let callers re-use Decoders and their
* [src/vendor/golang.org/x/net/http2/hpack/hpack.go:216](src/vendor/golang.org/x/net/http2/hpack/hpack.go#L216): remove this method and make it incremental later? This is
* [src/vendor/golang.org/x/net/http2/hpack/hpack.go:468](src/vendor/golang.org/x/net/http2/hpack/hpack.go#L468): proper overflow check. making this up.
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:315](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L315): profiles
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:33](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L33): the current error handling is, in my opinion, the least opinionated.
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:347](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L347): allow for a quick check of the tables data.
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:428](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L428): consider first doing a quick check to see if any of these checks
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:437](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L437): filter need for normalization in loop below.
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:449](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L449): handle the NV8 defined in the Unicode idna data set to allow
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:465](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L465): also store bidi info for mapped data. This is possible, but a bit
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:532](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L532): the punycode converters require strings as input.
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:620](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L620): handle V2008
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:630](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L630): detect whether string may have to be normalized in the following
* [src/vendor/golang.org/x/net/idna/idna10.0.0.go:728](src/vendor/golang.org/x/net/idna/idna10.0.0.go#L728): merge the use of this in the trie.
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:317](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L317): profiles
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:32](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L32): the current error handling is, in my opinion, the least opinionated.
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:430](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L430): handle the NV8 defined in the Unicode idna data set to allow
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:482](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L482): the punycode converters require strings as input.
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:570](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L570): handle V2008
* [src/vendor/golang.org/x/net/idna/idna9.0.0.go:676](src/vendor/golang.org/x/net/idna/idna9.0.0.go#L676): merge the use of this in the trie.
* [src/vendor/golang.org/x/net/idna/trie12.0.0.go:21](src/vendor/golang.org/x/net/idna/trie12.0.0.go#L21): support and handle two-byte inline masks
* [src/vendor/golang.org/x/net/idna/trie13.0.0.go:21](src/vendor/golang.org/x/net/idna/trie13.0.0.go#L21): support and handle two-byte inline masks
* [src/vendor/golang.org/x/text/secure/bidirule/bidirule.go:269](src/vendor/golang.org/x/text/secure/bidirule/bidirule.go#L269): is this correct?
* [src/vendor/golang.org/x/text/secure/bidirule/bidirule.go:275](src/vendor/golang.org/x/text/secure/bidirule/bidirule.go#L275): using CompactClass would result in noticeable speedup.
* [src/vendor/golang.org/x/text/secure/bidirule/bidirule.go:314](src/vendor/golang.org/x/text/secure/bidirule/bidirule.go#L314): using CompactClass results in noticeable speedup.
* [src/vendor/golang.org/x/text/transform/transform.go:204](src/vendor/golang.org/x/text/transform/transform.go#L204): implement ReadByte (and ReadRune??).
* [src/vendor/golang.org/x/text/transform/transform.go:238](src/vendor/golang.org/x/text/transform/transform.go#L238): limit the amount copied on first try.
* [src/vendor/golang.org/x/text/transform/transform.go:404](src/vendor/golang.org/x/text/transform/transform.go#L404): make chain use Span (is going to be fun to implement!)
* [src/vendor/golang.org/x/text/transform/transform.go:605](src/vendor/golang.org/x/text/transform/transform.go#L605): let transformers implement an optional Spanner interface, akin
* [src/vendor/golang.org/x/text/unicode/bidi/bidi.go:164](src/vendor/golang.org/x/text/unicode/bidi/bidi.go#L164): what happens if the position is > len(input)? This should return an error.
* [src/vendor/golang.org/x/text/unicode/bidi/bidi.go:280](src/vendor/golang.org/x/text/unicode/bidi/bidi.go#L280): perhaps with options.
* [src/vendor/golang.org/x/text/unicode/bidi/bidi.go:304](src/vendor/golang.org/x/text/unicode/bidi/bidi.go#L304): methods for
* [src/vendor/golang.org/x/text/unicode/bidi/bracket.go:232](src/vendor/golang.org/x/text/unicode/bidi/bracket.go#L232): have separate type for "strong" directionality.
* [src/vendor/golang.org/x/text/unicode/bidi/bracket.go:251](src/vendor/golang.org/x/text/unicode/bidi/bracket.go#L251): use separate type for "strong" directionality.
* [src/vendor/golang.org/x/text/unicode/bidi/prop.go:17](src/vendor/golang.org/x/text/unicode/bidi/prop.go#L17): using this for bidirule reduces the running time by about 5%. Consider
* [src/vendor/golang.org/x/text/unicode/bidi/prop.go:43](src/vendor/golang.org/x/text/unicode/bidi/prop.go#L43): find a better API and expose.
* [src/vendor/golang.org/x/text/unicode/bidi/prop.go:67](src/vendor/golang.org/x/text/unicode/bidi/prop.go#L67): these lookup methods are based on the generated trie code. The returned
* [src/vendor/golang.org/x/text/unicode/norm/composition.go:239](src/vendor/golang.org/x/text/unicode/norm/composition.go#L239): inline.
* [src/vendor/golang.org/x/text/unicode/norm/forminfo.go:108](src/vendor/golang.org/x/text/unicode/norm/forminfo.go#L108): loosen these conditions.
* [src/vendor/golang.org/x/text/unicode/norm/forminfo.go:149](src/vendor/golang.org/x/text/unicode/norm/forminfo.go#L149): create the decomposition for Hangul?
* [src/vendor/golang.org/x/text/unicode/norm/iter.go:249](src/vendor/golang.org/x/text/unicode/norm/iter.go#L249): this condition should not be possible, but we leave it
* [src/vendor/golang.org/x/text/unicode/norm/normalize.go:444](src/vendor/golang.org/x/text/unicode/norm/normalize.go#L444): Using streamSafe to determine the boundary isn't the same as
* [src/vendor/golang.org/x/text/unicode/norm/normalize.go:511](src/vendor/golang.org/x/text/unicode/norm/normalize.go#L511): this could be removed if we don't support merging.
* [src/vendor/golang.org/x/text/unicode/norm/transform.go:56](src/vendor/golang.org/x/text/unicode/norm/transform.go#L56): get rid of reorderBuffer. See CL 23460044.
* [test/codegen/comparisons.go:369](test/codegen/comparisons.go#L369): optimize 'var - var'
* [test/codegen/memcombine.go:367](test/codegen/memcombine.go#L367): Note that
* [test/escape2.go:668](test/escape2.go#L668): This one really only escapes its scope, but we don't distinguish yet.
* [test/escape2n.go:668](test/escape2n.go#L668): This one really only escapes its scope, but we don't distinguish yet.
* [test/fixedbugs/issue20335.go:10](test/fixedbugs/issue20335.go#L10): check the generated assembly?
* [test/fixedbugs/issue22662.go:8](test/fixedbugs/issue22662.go#L8): check columns
* [test/fuse.go:48](test/fuse.go#L48): Add support for floating point numbers in prove
* [test/prove.go:1712](test/prove.go#L1712): can't get rid of this bounds check yet
* [test/typeparam/dedup.go:10](test/typeparam/dedup.go#L10): automate this somehow?
* [test/typeparam/issue48094.dir/main.go:16](test/typeparam/issue48094.dir/main.go#L16): enable once 47631 is fixed.
