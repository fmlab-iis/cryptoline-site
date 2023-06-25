---
title: "Tutorial"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

{{< katex display >}}
\gdef{\mZ}{{\mathbb{Z}}}
\gdef{\mN}{{\mathbb{N}}}

\gdef{\xeightysix}{x86\_64}

\gdef{\cryptoline}{\textrm{CryptoLine}}
\gdef{\openssl}{\textrm{OpenSSL}}
\gdef{\blst}{\textrm{blst}}
\gdef{\pqclean}{\textrm{PQClean}}
\gdef{\pqmfour}{\textrm{pqm4}}
\gdef{\python}{\textrm{Python}}
\gdef{\gdb}{\textrm{gdb}}
\gdef{\ocaml}{\textrm{OCaml}}
\gdef{\opam}{\textrm{opam}}
\gdef{\boolector}{\textrm{boolector}}
\gdef{\singular}{\textrm{Singular}}
\gdef{\ubuntu}{\textrm{ubuntu}}

\gdef{\derefop}{\mathit{\$}}
\gdef{\deref}#1{\mathit{\$#1}}
\gdef{\wordsize}{W}
\gdef{\prog}{\mathit{prog}}
\gdef{\stmt}{\mathit{stmt}}
\gdef{\proc}{\mathit{proc}}
\gdef{\formals}{\mathit{formals}}
\gdef{\true}{\mathit{true}}
\gdef{\minusop}{-}
\gdef{\eqop}{=}
\gdef{\negop}{\sim}
\gdef{\addop}{+}
\gdef{\subop}{-}
\gdef{\mulop}{*}
\gdef{\powop}{**}
\gdef{\landop}{\mathit{/\backslash}}
\gdef{\lorop}{\mathit{\backslash/}}
\gdef{\notop}{!}
\gdef{\andop}{\mathit{\text{\&}}}
\gdef{\orop}{\mathit{|}}
\gdef{\xorop}{\mathit{\text{\textasciicircum}}}
\gdef{\ultop}{\mathit{<}}
\gdef{\uleop}{\mathit{<=}}
\gdef{\ugtop}{\mathit{>}}
\gdef{\ugeop}{\mathit{>=}}
\gdef{\sltop}{\mathit{<s}}
\gdef{\sleop}{\mathit{<=s}}
\gdef{\sgtop}{\mathit{>s}}
\gdef{\sgeop}{\mathit{>=s}}
\gdef{\iult}{\mathit{ult}}
\gdef{\iule}{\mathit{ule}}
\gdef{\iugt}{\mathit{ugt}}
\gdef{\iuge}{\mathit{uge}}
\gdef{\islt}{\mathit{slt}}
\gdef{\isle}{\mathit{sle}}
\gdef{\isgt}{\mathit{sgt}}
\gdef{\isge}{\mathit{sge}}
\gdef{\pre}{\mathit{pre}}
\gdef{\post}{\mathit{post}}
\gdef{\pred}{\mathit{pred}}
\gdef{\epred}{\mathit{epred}}
\gdef{\rpred}{\mathit{rpred}}
\gdef{\predclause}{\mathit{pred\_clause}}
\gdef{\epredclause}{\mathit{epred\_clause}}
\gdef{\rpredclause}{\mathit{rpred\_clause}}
\gdef{\iuext}{\mathit{uext}}
\gdef{\isext}{\mathit{sext}}
\gdef{\imod}{\mathit{mod}}
\gdef{\iumod}{\mathit{umod}}
\gdef{\ismod}{\mathit{smod}}
\gdef{\isrem}{\mathit{srem}}
\gdef{\ilimbs}{\mathit{limbs}}
\gdef{\eexp}{\mathit{eexp}}
\gdef{\rexp}{\mathit{rexp}}
\gdef{\instr}{\mathit{instr}}
\gdef{\imov}{\mathit{mov}}
\gdef{\iadd}{\mathit{add}}
\gdef{\iuadd}{\mathit{uadd}}
\gdef{\isadd}{\mathit{sadd}}
\gdef{\iadds}{\mathit{adds}}
\gdef{\iuadds}{\mathit{uadds}}
\gdef{\isadds}{\mathit{sadds}}
\gdef{\iaddr}{\mathit{addr}}
\gdef{\iuaddr}{\mathit{uaddr}}
\gdef{\isaddr}{\mathit{saddr}}
\gdef{\iadc}{\mathit{adc}}
\gdef{\iuadc}{\mathit{uadc}}
\gdef{\isadc}{\mathit{sadc}}
\gdef{\iadcs}{\mathit{adcs}}
\gdef{\iuadcs}{\mathit{uadcs}}
\gdef{\isadcs}{\mathit{sadcs}}
\gdef{\iadcr}{\mathit{adcr}}
\gdef{\iuadcr}{\mathit{uadcr}}
\gdef{\isadcr}{\mathit{sadcr}}
\gdef{\isub}{\mathit{sub}}
\gdef{\iusub}{\mathit{usub}}
\gdef{\issub}{\mathit{ssub}}
\gdef{\isubs}{\mathit{subs}}
\gdef{\iusubs}{\mathit{usubs}}
\gdef{\issubs}{\mathit{ssubs}}
\gdef{\isubc}{\mathit{subc}}
\gdef{\iusubc}{\mathit{usubc}}
\gdef{\issubc}{\mathit{ssubc}}
\gdef{\isubb}{\mathit{subb}}
\gdef{\iusubb}{\mathit{usubb}}
\gdef{\issubb}{\mathit{ssubb}}
\gdef{\isubr}{\mathit{subr}}
\gdef{\iusubr}{\mathit{usubr}}
\gdef{\issubr}{\mathit{ssubr}}
\gdef{\isbc}{\mathit{sbc}}
\gdef{\iusbc}{\mathit{usbc}}
\gdef{\issbc}{\mathit{ssbc}}
\gdef{\isbcs}{\mathit{sbcs}}
\gdef{\iusbcs}{\mathit{usbcs}}
\gdef{\issbcs}{\mathit{ssbcs}}
\gdef{\isbcr}{\mathit{sbcr}}
\gdef{\iusbcr}{\mathit{usbcr}}
\gdef{\issbcr}{\mathit{ssbcr}}
\gdef{\isbb}{\mathit{sbb}}
\gdef{\iusbb}{\mathit{usbb}}
\gdef{\issbb}{\mathit{ssbb}}
\gdef{\isbbs}{\mathit{sbbs}}
\gdef{\iusbbs}{\mathit{usbbs}}
\gdef{\issbbs}{\mathit{ssbbs}}
\gdef{\isbbr}{\mathit{sbbr}}
\gdef{\iusbbr}{\mathit{usbbr}}
\gdef{\issbbr}{\mathit{ssbbr}}
\gdef{\imul}{\mathit{mul}}
\gdef{\iumul}{\mathit{umul}}
\gdef{\ismul}{\mathit{smul}}
\gdef{\imuls}{\mathit{muls}}
\gdef{\iumuls}{\mathit{umuls}}
\gdef{\ismuls}{\mathit{smuls}}
\gdef{\imulr}{\mathit{mulr}}
\gdef{\iumulr}{\mathit{umulr}}
\gdef{\ismulr}{\mathit{smulr}}
\gdef{\imull}{\mathit{mull}}
\gdef{\iumull}{\mathit{umull}}
\gdef{\ismull}{\mathit{smull}}
\gdef{\imulj}{\mathit{mulj}}
\gdef{\iumulj}{\mathit{umulj}}
\gdef{\ismulj}{\mathit{smulj}}
\gdef{\isplit}{\mathit{split}}
\gdef{\ispl}{\mathit{spl}}
\gdef{\ijoin}{\mathit{join}}
\gdef{\ishl}{\mathit{shl}}
\gdef{\ishls}{\mathit{shls}}
\gdef{\ishr}{\mathit{shr}}
\gdef{\ishrs}{\mathit{shrs}}
\gdef{\isar}{\mathit{sar}}
\gdef{\isars}{\mathit{sars}}
\gdef{\icshl}{\mathit{cshl}}
\gdef{\icshr}{\mathit{cshr}}
\gdef{\icshrs}{\mathit{cshrs}}
\gdef{\iset}{\mathit{set}}
\gdef{\iclear}{\mathit{clear}}
\gdef{\inondet}{\mathit{nondet}}
\gdef{\icmov}{\mathit{cmov}}
\gdef{\ieq}{\mathit{eq}}
\gdef{\ieqmod}{\mathit{eqmod}}
\gdef{\iequmod}{\mathit{equmod}}
\gdef{\ieqsmod}{\mathit{eqsmod}}
\gdef{\ieqsrem}{\mathit{eqsrem}}
\gdef{\ineg}{\mathit{neg}}
\gdef{\iand}{\mathit{and}}
\gdef{\ior}{\mathit{or}}
\gdef{\ixor}{\mathit{xor}}
\gdef{\inot}{\mathit{not}}
\gdef{\iassert}{\mathit{assert}}
\gdef{\iassume}{\mathit{assume}}
\gdef{\ighost}{\mathit{ghost}}
\gdef{\icut}{\mathit{cut}}
\gdef{\iecut}{\mathit{ecut}}
\gdef{\ircut}{\mathit{rcut}}
\gdef{\icast}{\mathit{cast}}
\gdef{\ivpc}{\mathit{vpc}}
\gdef{\icall}{\mathit{call}}
\gdef{\inop}{\mathit{nop}}
\gdef{\iconst}{\mathit{const}}
\gdef{\iprove}{\mathit{prove}}
\gdef{\iwith}{\mathit{with}}
\gdef{\provewith}{\mathit{prove\_with}}
\gdef{\precondition}{\mathit{precondition}}
\gdef{\all}{\mathit{all}}
\gdef{\cuts}{\mathit{cuts}}
\gdef{\assumes}{\mathit{assumes}}
\gdef{\ghosts}{\mathit{ghosts}}
\gdef{\algebra}{\mathit{algebra}}
\gdef{\range}{\mathit{range}}
\gdef{\solver}{\mathit{solver}}
\gdef{\varseq}{\mathit{varseq}}
\gdef{\atom}{\mathit{atom}}
\gdef{\atomseq}{\mathit{atomseq}}
\gdef{\var}{\mathit{var}}
\gdef{\tvar}{\mathit{typed\_var}}
\gdef{\lval}{\mathit{lval}}
\gdef{\simpleconst}{\mathit{simple\_const}}
\gdef{\complexconst}{\mathit{complexy\_const}}
\gdef{\const}{\mathit{const}}
\gdef{\tconst}{\mathit{typed\_const}}
\gdef{\id}{\mathit{id}}
\gdef{\path}{\mathit{path}}
\gdef{\smt}{\mathit{smt}}
\gdef{\cas}{\mathit{cas}}
\gdef{\singularsolver}{\mathit{singular}}
\gdef{\sagesolver}{\mathit{sage}}
\gdef{\magmasolver}{\mathit{magma}}
\gdef{\mathematicasolver}{\mathit{mathematica}}
\gdef{\macaulaysolver}{\mathit{macaulay2}}
\gdef{\maplesolver}{\mathit{maple}}
\gdef{\typ}{\mathit{typ}}
\gdef{\letter}{\mathit{letter}}
\gdef{\digit}{\mathit{digit}}
\gdef{\underscore}{\mathit{underscore}}
\gdef{\uint}{\mathsf{uint}}
\gdef{\sint}{\mathsf{sint}}
\gdef{\bit}{\mathsf{bit}}
\gdef{\band}{\&\&}
{{< /katex >}}

## Introduction

$\cryptoline$ is a verificaiton tool chain for cryptographic assembly
programs. It contains the $\cryptoline$ model checker and tools for
building models from executable binary codes. $\cryptoline$ is designed
for verifying algebraic properties in cryptographic programs. It has
been used to verify cryptographic assembly programs in $\openssl$ and
$\blst$, $\pqclean$, and $\pqmfour$.

In this tutorial, we explain notable features of $\cryptoline$ through
two running examples from $\xeightysix$ implementations for NIST P-256 curve
in $\openssl$. Specifically, NIST P-256 curve uses the finite field
$\mZ_{p256}$ where $p256$ is

\\[
\mathtt{0xffffffff00000001\ 0000000000000000\ 00000000ffffffff\ ffffffffffffffff}.
\\]

We will verify the addition (`ecp_nistz256_add`)
and Montegomery multiplication (`ecp_nistz256_mul_montx`)
over the field $\mZ_{p256}$ from `crypto/ec/asm` in $\openssl$.
All $\cryptoline$ codes can be found in
`examples/openss/ecp_nistz256/x86_64` from the $\cryptoline$
distribution.

## $\cryptoline$ Overview

To verify cryptographic programs with $\cryptoline$, a verifier has to
construct program models written in the $\cryptoline$ language. Such
program models could be written manually. Manual construction
nevertheless could be tedious or even deviant from real cryptographic
programs. To help verifiers, $\cryptoline$ provides a $\python$ script
`itrace.py` to extract traces from running cryptographic
programs in $\gdb$. Verifiers will obtain traces of cryptographic
programs as executed on hardware. Since traces are extracted from
$\gdb$, they are sequences of assembly instructions from the underlying
hardware architecture. To convert such traces to $\cryptoline$ models,
$\cryptoline$ provides another $\python$ script `to_zdsl.py` to
help verifiers transliate assembly instructions to $\cryptoline$
commands. Through `itrace.py` and `to_zdsl.py`, accurate $\cryptoline$ models can
be constructed rather easily. They are indispensable in practice.

Based on the $\cryptoline$ models generated by `to_zdsl.py`, verifiers need to
annotate models with input assumptions (or *pre-conditions*) and
output requirements (or *post-conditions*). Additional
annotations are aften required to guide $\cryptoline$ verification
engines as well. After necessary annotations are added, the $\cryptoline$
verification tool will prove if all post-conditions must hold under
pre-conditions automatically. If $\cryptoline$ fails to prove
post-conditions, hints can be found in $\cryptoline$ log files.
Verifiers can decide whether more annotations are needed or bugs are
found from the hints.

The $\cryptoline$ verification tool employs two engines for proving
different properties about $\cryptoline$ models. The SMT-based engine
calls an external SMT QFBV (Satisfiability Modulo Quantifier-Free
Bit-Vector Theory) solver to prove range properties. The CAS-based
engine calls an external CAS (Computer Algebra System) to prove
algebraic properties. Generally, the SMT-based engine is automatic but
unsuitable for complex non-linear algebraic properties. The CAS-based
engine on the other hand is much better for algebraic properties but
requires more annotations. Verifiers need to choose which engine to
use by their discretion.

## Installing $\cryptoline$

$\cryptoline$ is an open-sourced project available at
<https://github.com/fmlab-iis/cryptoline>. To download its source
code, type

```bash
$ git clone https://github.com/fmlab-iis/cryptoline.git
```

$\cryptoline$ is written in $\ocaml$ and requires the $\ocaml$ package
manager $\opam$, external SMT solvers, and CAS's. Use the following
commands to install the $\opam$ package manager, the SMT solver
$\boolector$, and the CAS $\singular$ in $\ubuntu$:

```bash
$ sudo apt-get install opam boolector singular-ui
```

Additional $\ocaml$ libraries are needed to compile $\cryptoline$. To
initialize $\opam$ and install these libraries, use the following
commands:

```bash
$ opam init --disable-sandboxing    # initialize opam
$ eval $(opam env)                  # set up environment variables
$ opam install dune lwt_ppx zarith  # install additional OCaml packages
```

Finally, go to the $\cryptoline$ directory and compile it with the
following commands:

```bash
$ cd cryptoline
$ dune build
```

The built $\cryptoline$ binaries are in the `_build/default`
directory. To make a symbolic link for convenience and check if
everything works fine, try

```bash
$ ln -s _build/default/cv.exe
$ cv.exe -v -isafety examples/openssl/ecp_nistz256/ecp_nistz256_mul_mont.cl
```

If you see messages similar to the folowing, you are all set!

```console
Parsing Cryptoline file:                [OK]            0.002074 seconds
Checking well-formedness:               [OK]            0.000732 seconds
Transforming to SSA form:               [OK]            0.000278 seconds
Normalizing specification:              [OK]            0.000017 seconds
Rewriting assignments:                  [OK]            0.000229 seconds
Verifying program safety:
         Cut 0
             Round 1 (32 safety conditions, timeout = 300 seconds)
                 Safety condition #3    [OK]
                 Safety condition #4    [OK]
                 Safety condition #0    [OK]
                 ...
                 Safety condition #28   [OK]
                 Safety condition #31   [OK]
         Overall                        [OK]            5.185277 seconds
Verifying range specification:          [OK]            2.155957 seconds
Rewriting value-preserved casting:      [OK]            0.000023 seconds
Verifying algebraic specification:      [OK]            0.107180 seconds
Verification result:                    [OK]            7.452392 seconds
```

## Running Examples from $\openssl$

The $\cryptoline$ verification tool is a model checker. That is, it
checks specified properties about models. To verify cryptographic
programs with $\cryptoline$, we need to write a model for the program
and specify properties about the model. In this tutorial, we will
verify the $\xeightysix$ assembly subroutines `ecp_nistz256_add`
and `__ecp_nistz256_mul_montx` from
`ecp_nistz256-x86_64.pl` in `crypto/ec/asm` from
$\openssl$. The subroutine `ecp_nistz256_add` takes two inputs
$a$ and $b$ from the field $\mZ_{p256}$, computes their sum $c \equiv
a + b \mod p256$, and stores $c$ in memory. The API for
`__ecp_nistz256_mul_montx` takes two inputs $a, b$ from
$\mZ_{p256}$, computes their Montgomery product $c \equiv a \times b
\times 2^{-256} \mod p256$, and stores $c$ in memory. They are used by
$\openssl$ on $\xeightysix$ by default. We will see important features of
$\cryptoline$ in these running examples.

### ecp_nistz256_add

#### Model Construction

The easiest way to construct accurate $\cryptoline$ models is by
extracting traces from execution. To do so, we need to build an
executable binary for the cryptographic program under
verification. Let us write a simple C program which calls the two
assembly subroutines.

```c
#include <stdint.h>
#define P256_LIMBS 4

typedef uint64_t BN_ULONG;

/* Modular add: res = a+b mod P   */
void ecp_nistz256_add(BN_ULONG res[P256_LIMBS],
                      const BN_ULONG a[P256_LIMBS],
                      const BN_ULONG b[P256_LIMBS]);
/* Montgomery mul: res = a*b*2^-256 mod P */
void ecp_nistz256_mul_mont(BN_ULONG res[P256_LIMBS],
                           const BN_ULONG a[P256_LIMBS],
                           const BN_ULONG b[P256_LIMBS]);

int main (void) {
  BN_ULONG a[P256_LIMBS], b[P256_LIMBS], r[P256_LIMBS];

  /* Modular add: res = a+b mod P   */
  ecp_nistz256_add(r, a, b);
  /* Montgomery mul: res = a*b*2^-256 mod P */
  ecp_nistz256_mul_mont(r, a, b);

  return 0;
}
```

An executable binary can be built with the following command
(`libcrypto.a` is from $\openssl$):

```bash
$ gcc -o top top.c libcrypto.a
```

$\cryptoline$ provides the $\python$ script `itrace.py` to extract execution
traces from $\gdb$. Write $\cryptoline$home for the root directory of
$\cryptoline$. The execution trace of `ecp_nistz256_add` is extracted with the
following command:

```bash
$ $CL_HOME/scripts/itrace.py top ecp_nistz256_add ecp_nistz256_add.gas
```

The first argument is the name of the executable binary `top`,
the second argument is the name of the subroutine `ecp_nistz256_add`, and the
third argument is the name of the output file
(`ecp_nistz256_add.gas`). The content of `ecp_nistz256_add.gas` looks like

```gas
ecp_nistz256_add:
# %rdi = 0x7fffffffda00
# %rsi = 0x7fffffffd9c0
# %rdx = 0x7fffffffd9e0
# %rcx = 0x7fffffffd9c0
# %r8  = 0x555555580c70
# %r9  = 0x7ffef3ff00000000
	#! -> SP = 0x7fffffffd9b8
	push   %r12                       #! EA = L0x7fffffffd9b0; ...
	push   %r13                       #! EA = L0x7fffffffd9a8; ...
	mov    (%rsi),%r8                 #! EA = L0x7fffffffd9c0; ...
	xor    %r13,%r13                  #! PC = 0x55555557c327
	mov    0x8(%rsi),%r9              #! EA = L0x7fffffffd9c8; ...
	mov    0x10(%rsi),%r10            #! EA = L0x7fffffffd9d0; ...
	mov    0x18(%rsi),%r11            #! EA = L0x7fffffffd9d8; ...
	lea    -0x33d(%rip),%rsi          # 0x55555557c000 ...
	add    (%rdx),%r8                 #! EA = L0x7fffffffd9e0; ...
	adc    0x8(%rdx),%r9              #! EA = L0x7fffffffd9e8; ...
        ...
```

The script `itrace.py` shows the register contents when `ecp_nistz256_add` is
called. By calling convention, `%rdi`, `%rsi`, and
`%rdx` contains the values of the first three arguments to
`ecp_nistz256_add`. In this case, we see the pointers `r[]`,
`a[]`, and `b[]` are `0x7fffffffda00`,
`0x7fffffffd9c0`, and `0x7fffffffd9e0`
respectively. For each instruction, `itrace.py` moreover reports the
effective address of its argument (`EA`), the value stored in
the address (`Value`), and the program counter (`C`).
The `itrace.py` script is necessarily architecture-dependent. It currently
supports ARM, MIPS, RISC-V, and x86. It can also connect to remote
$\gdb$ through a serial port. It has been used to extract traces from
ARM Cortex-M4 development boards.

Our next step is to convert $\xeightysix$ instructions to corresponding
$\cryptoline$ commands. $\cryptoline$ provides the $\python$ script `to_zdsl.py`
to convert instructions by writing translation rules. Translation
rules are specified in the beginning of execution traces
(`ecp_nistz256_add.gas`). They must start with `#!`. For `to_zdsl.py`,
strings prefixed by `%%` are matched differently. We start
with rules for such strings:

```console
#! $1c(%rdi) = %%EA
#! (%rdi) = %%EA
#! $1c(%rsi) = %%EA
#! (%rsi) = %%EA
#! $1c(%rdx) = %%EA
#! (%rdx) = %%EA
#! %r$1c = %%r$1c
#! %rax = %%rax
#! %rcx = %%rcx
#! %rdx = %%rdx
```

The left hand side denotes the string in the trace to be matched. The
right hand side denotes how to rewrite the match strings. The notations
`$1c`, `$2c`, and so on match constants. The first six
rules rewrite memory references to `%%EA`. The last four
rules add an additional `%` to registers.

For each $\xeightysix$ instruction in `ecp_nistz256_add.gas`, a translation rule is
needed for conversion. Instructions starting with `#` will be
skipped. Let us look at the rule for the $\xeightysix$ `xor` instruction:

```console
#! xor $1v, $1v -> mov $1v 0@uint64
```

The left hand side denotes the pattern in the trace to be matched. The
right hand side denotes how to rewrite the matched pattern. The strings
prefixed with `%%` are matched by `$1v`,
`\$2v`, and so on. The $\xeightysix$ instructions from the trace
separate arguments by `,`. They moreover write sources before
destinations. The $\cryptoline$ commands however write destinations
before sources. In this rule, the same register appears in both
arguments to the `xor` instruction. The register is set to
zero effectively. The rule thus sets the $\cryptoline$ variable to
`0@uint64`. Note that all constants in $\cryptoline$ must be
given a type. The notation `0@uint64` denotes the constant zero
of the unsigned 64-bit integer type.

Our next rules are for the $\xeightysix$ `mov` instruction:

```console
#! mov $1v, $2v -> mov $2v $1v
#! mov $1ea, $2v -> mov $2v $1ea
#! mov $1v, $2ea -> mov $2ea $1v
```

The string `%%EA` is matched by `$1ea`,
`$2ea`, and so on. Recall that `itrace.py` reports the effective
address appeared in each instruction. The script `to_zdsl.py` will also
rewrite each matched `%%EA` to the corresponding effective
address. In $\cryptoline$, there is no memory model. All memory stores
are modeled by $\cryptoline$ variables. By convention, the memory store
with the address `addr` are modeled by the variable
`Laddr`. Using effective addresses as variable names
allows us to avoid tedious address computation. It greatly simplifies
our model construnction. Our rules simply swap the order of source and
destination.

The rules for arithmetic instructions are also strightforward:

```console
#! add $1ea, $2v -> adds carry $2v $2v $1ea
#! adc $1ea, $2v -> adcs carry $2v $2v $1ea carry
#! adc \$0x0, $1v -> adc $1v $1v 0@uint64 carry
#! sub $1ea, $2v -> subb carry $2v $2v $1ea
#! sbb $1ea, $2v -> sbbs carry $2v $2v $1ea carry
#! sbb \$0x0, $1v -> sbbs carry $1v $1v 0@uint64 carry
```

In $\cryptoline$ commands, all arguments are explicit. Consider, for
instance, the $\xeightysix$ `add` instruction. It puts the sum of the
two arguments in the destination *and* sets the carry flag
implicitly. In $\cryptoline$, two commands are provided for addition:
`add` updates the destination with the sum of sources;
`adds` updates the destination with the sume of sources
*and* the destination flag with carry. In our rules, the
$\cryptoline$ variable `carry` denotes the carry flag. We
therefore use the `adds` and `adcs` for the $\xeightysix$
`add` and `adc` instructions respectively. Finally,
$\cryptoline$ provides subtraction commands for carry or borrow
flags. The `subb` commands updates the destination with the
difference of sources and the destination flag with *borrow*; the
`subc` commands updates the destination with the difference of
sources and the destination flag with *carry*. In $\xeightysix$, the
`sub` instruction updates the carry flag with borrow. Our rule
hence uses the $\cryptoline$ `subb` command.

Our last rule is for the $\xeightysix$ `cmovb` instruction:

```console
#! cmovb $1v, $2v -> cmov $2v carry $1v $2v
```

The instruction sets the destination to the value of source if the
carry flag is true. The $\cryptoline$ command `cmov` sets the
destination to the value of the first source if the source flag is
true; it sets the destination to the value of the second source
otherwise.

After putting all translation rules in the beginning of `ecp_nistz256_add.gas`,
the $\xeightysix$ trace can be converted to a $\cryptoline$ model with
following command:

```bash
$ $CL_HOME/script/to_zdsl.py ecp_nistz256_add.gas > ecp_nistz256_add.cl
```

The content of `ecp_nistz256_add.cl` looks like:

```console
proc main (L0x55555557c000, ...) =
{
  true
  &&
  true
}

(* #! -> SP = 0x7fffffffd9b8 *)
#! 0x7fffffffd9b8 = 0x7fffffffd9b8;
(* #push   %r12                     #! ...                       *)
#push   %%r12                       #! ...
(* #push   %r13                     #! ...                       *)
#push   %%r13                       #! ...
(* mov    (%rsi),%r8                #! EA = L0x7fffffffd9c0; ... *)
mov r8 L0x7fffffffd9c0;
(* xor    %r13,%r13                 #! PC = 0x55555557c327 *)
mov r13 0@uint64;
...
(* #repz retq                       #! PC = 0x55555557c39c *)
#repz retq                          #! ...

{
  true
  &&
  true
}
```

The notation `proc main (...) =` denotes the main subroutine in
$\cryptoline$. The arguments to the main subroutine are the
uninitialized variables reported by `to_zdsl.py`. In this case, they are
memory stores for input arguments and constants used in `ecp_nistz256_add`. The
expression in the brackets `true && true` denote the
pre-condition. It is followed by $\cryptoline$ commands for $\xeightysix$
instructions. Each $\xeightysix$ instruction is put in $\cryptoline$
comments prefixed by `#` or enclosed by `(*` and
`*)`. It is then followed by the $\cryptoline$ command generated
with the translation rules. Finally, the expression in the ending
brackets `true && true` denotes the post-condition.

Let us first make arguments more readable by replacing the main
subroutine declaration with:

```console
proc main (uint64 a0, uint64 a1, uint64 a2, uint64 a3,
           uint64 b0, uint64 b1, uint64 b2, uint64 b3,
           uint64 m0, uint64 m1, uint64 m2, uint64 m3) =
```

We will use `a`'s and `b`'s for the two input elements
and `m`'s for the modulo $p256$. The pre-condition for the main
subroutine is

```console
{
  true
  &&
  and [ m0 = 0xffffffffffffffff@64, m1 = 0x00000000ffffffff@64,
        m2 = 0x0000000000000000@64, m3 = 0xffffffff00000001@64,
        limbs 64 [a0, a1, a2, a3] <u limbs 64 [m0, m1, m2, m3],
        limbs 64 [b0, b1, b2, b3] <u limbs 64 [m0, m1, m2, m3]
  ]
}
```

Recall that two different engines are employed in $\cryptoline$. In
order to differentiate properties passed to different engines, all
$\cryptoline$ properties are of the form `P &&
Q`: `P` is passed to CAS's and `Q` is to SMT
solvers. For `ecp_nistz256_add`, the SMT-based engine suffices because it does
not involve non-linear computation. Our pre-condition simply passes
`true` to the CAS-based engine. For the SMT-based engine, the
pre-condition assumes `m`'s to be the modulo $p256$. The field
elements `a`'s and `b`'s moreover are less than $p256$
in the unsigned representation. The expression `limbs n
[a0, a1, ..., am]` is short for

\\[
  a_0\times 2^{0\times n}+a_1\times 2^{1\times n}+\cdots+a_m\times
  2^{m\times n}.
\\]

Our next step is to put input field elements and constants to
correspond memory stores. By consulting `ecp_nistz256_add.gas`, we add the
following $\cryptoline$ commands after the pre-condition:

```console
mov L0x7fffffffd9c0 a0; mov L0x7fffffffd9c8 a1;
mov L0x7fffffffd9d0 a2; mov L0x7fffffffd9d8 a3;

mov L0x7fffffffd9e0 b0; mov L0x7fffffffd9e8 b1;
mov L0x7fffffffd9f0 b2; mov L0x7fffffffd9f8 b3;

mov L0x55555557c000 0xffffffffffffffff@uint64;
mov L0x55555557c008 0x00000000ffffffff@uint64;
mov L0x55555557c010 0x0000000000000000@uint64;
mov L0x55555557c018 0xffffffff00000001@uint64;
```

At the end of `ecp_nistz256_add.cl`, we copy the result from memory stores by
the following command:

```console
mov c0 L0x7fffffffda00; mov c1 L0x7fffffffda08;
mov c2 L0x7fffffffda10; mov c3 L0x7fffffffda18;
```

Finally, we specify the post-condition for the SMT-based engine:

```console
{
  true &&
  and [ eqmod limbs 64 [c0, c1, c2, c3, 0@64]
              limbs 64 [a0, a1, a2, a3, 0@64] +
              limbs 64 [b0, b1, b2, b3, 0@64]
              limbs 64 [m0, m1, m2, m3, 0@64],
        limbs 64 [c0, c1, c2, c3] <u limbs 64 [m0, m1, m2, m3] ]
}
```

The post-condition states that the output field element `c`'s
is congruent to the sum of input field elements modulo $p256$, and the
output field element is less than the modulo in the unsigned
representation. Note that the congruence is computed with $5\times
64=320$ bits instead of $256$ bits.

#### Verification

We are ready to verify our $\cryptoline$ model for `ecp_nistz256_add`. Try

```bash
$ $CL_HOME/cv.exe -v -isafety ecp_nistz256_add.cl
```

The transcript is shown below:

```console
Parsing Cryptoline file:                [OK]            0.001247 seconds
Checking well-formedness:               [OK]            0.000218 seconds
Transforming to SSA form:               [OK]            0.000105 seconds
Normalizing specification:              [OK]            0.000097 seconds
Rewriting assignments:                  [OK]            0.000122 seconds
Verifying program safety:
         Cut 0
             Round 1 (1 safety conditions, timeout = 300 seconds)
                 Safety condition #0    [OK]
         Overall                        [OK]            0.044187 seconds
Verifying range specification:          [OK]            2.203067 seconds
Rewriting value-preserved casting:      [OK]            0.000023 seconds
Verifying algebraic specification:      [OK]            0.000412 seconds
Verification result:                    [OK]            2.249944 seconds
```

Congratulations! You have verified the $\xeightysix$ `ecp_nistz256_add`
subroutine in $\openssl$ successfully. As we have seen, $\cryptoline$
provides useful scripts for model construction. They are not perfect
and still require human intervention. Some practices will help
verifiers get familiar with the verification flow.

**Exercise:** Construct a model for `ecp_nistz256_sub` in
`ecp_nistz256-x86_64.pl` and verify it.

### ecp_nistz256_mul_mont

Our next example is to verify the assembly subroutine `ecp_nistz256_mul_mont` from
$\openssl$.[^1] The assembly subroutine
takes two field elements $a$ and $b$ in $\mZ_{p256}$ as inputs,
computes their Montgomery product $c$, and store $c$ in
memory. Mathematically, the inputs and output satisfy the following
modular equation:

\\[
c \equiv a \times b \times 2^{-256} \mod p256
\\]
equivalently,
\\[
c \times 2^{256} \equiv a \times b \mod p256
\\]

[^1]: Depending on the
$\xeightysix$ microarchitecture, the assembly subroutine `ecp_nistz256_mul_mont`
has two implementations: `__ecp_nistz256_mul_montx` and
`__ecp_nistz256_mul_montq`. We will verify
`__ecp_nistz256_mul_montx` here.

#### Model Construction

The executable binary
`top` built in the first example also calls the assembly
subroutine. The trace for `ecp_nistz256_mul_mont` can be extracted by `itrace.py` with
the same binary:

```bash
$ $CL_HOME/scripts/itrace.py top ecp_nistz256_mul_mont ecp_nistz256_mul_mont.gas
```

The trace `ecp_nistz256_mul_mont.gas` looks like the following:

```console
ecp_nistz256_mul_mont:
# %rdi = 0x7fffffffd9f0
# %rsi = 0x7fffffffd9b0
# %rdx = 0x7fffffffd9d0
# %rcx = 0x7fffffffd9b0
# %r8  = 0x-9
# %r9  = 0xfffffffe
	#! -> SP = 0x7fffffffd9a8
	mov    $0x80100,%ecx            #! PC = 0x55555557d1e0
	and    0x5e35(%rip),%ecx        # ...
	push   %rbp                     #! EA = L0x7fffffffd9a0; ...
	push   %rbx                     #! EA = L0x7fffffffd998; ...
        ...
```

By calling convention, we know the input field elements are stored at
`0x7fffffffd9b0` and `0x7fffffffd9d0`; the output is
stored at `0x7fffffffd9f0`. The subroutine uses more
registers. Unsurprisingly, we need additional translation rules for
memory addresses and registers.

```console
#! $1c(%rdi) = %%EA
#! (%rdi) = %%EA
#! $1c(%rsi) = %%EA
#! (%rsi) = %%EA
#! $1c(%rdx) = %%EA
#! (%rdx) = %%EA
#! $1c(%rbx) = %%EA
#! (%rbx) = %%EA
#! -$1c(%rip) = %%EA
#! %r$1c = %%r$1c
#! %rax = %%rax
#! %rbx = %%rbx
#! %rcx = %%rcx
#! %rdx = %%rdx
#! %rbp = %%rbp
#! %eax = %%eax
```

Many translation rules for $\xeightysix$ instructions can be
re-used. They are listed below:

```console
#! add $1v, $2v -> adds carry $2v $2v $1v
#! adc $1v, $2v -> adcs carry $2v $2v $1v carry
#! cmovb $1v, $2v -> cmov $2v carry $1v $2v
#! mov $1c, $2v -> mov $2v $1c@uint64
#! mov $1v, $2v -> mov $2v $1v
#! mov $1ea, $2v -> mov $2v $1ea
#! mov $1v, $2ea -> mov $2ea $1v
#! sbb $1v, $2v -> sbbs carry $2v $2v $1v carry
```

Three rules are modified slightly. They are:

```console
#! xor $1v, $1v -> mov $1v 0@uint64;\nclear carry;\nclear overflow
#! adc $1c, $2v -> adc $2v $2v $1c@uint64 carry
#! sbb $1c, $2v -> sbbs carry $2v $2v $1c@uint64 carry
```

The $\xeightysix$ `xor` instruction actually clears carry and
overflow flags. This is not modeled previously but needed in
`ecp_nistz256_mul_mont`, so the rule is modified accordingly. The string
`\n` represents a line break. In `ecp_nistz256_mul_mont`, more
constant literals are used. We therefore use `$1c` to match
constants in the rules for `adc` and `sbb`.

Two addtional addition instructions are used in `ecp_nistz256_mul_mont`. The
`adcx` and `adox` instructions compute the sum with the
carry and overflow flags as carry respectively. Their translation
rules are similar to those for `adc`:

```console
#! adcx $1v, $2v -> adcs carry $2v $2v $1v carry
#! adox $1v, $2v -> adcs overflow $2v $2v $1v overflow
```

The $\xeightysix$ `mulx` computes the product of the `rdx`
register and the source. The 128-bit product is then stored in the
destinations. The $\cryptoline$ `mull` command computes the
product of the last two arguments, stores the more significant half
in the first argument and the less significant half in the second. We
thus use the following rule for `mulx`:

```console
#! mulx $1v, $2v, $3v -> mull $3v $2v rdx $1v
```

Finally, the $\xeightysix$ instruction `shlx r s d` and
`shrx r s d` shifts the value of `s` to the left and
right respectively by the value in `r`. The shifted
result is stored in `d`. In $\cryptoline$, the
`shl d s c` shifts the value of
`s` by the constant `c` bits to the
left. The `split h l s c`
command splits `s` by the constant `c`
into two parts: the lowest `c` bits are stored in
`l` and other bits are stored in `h`.
It is tempting to use the following rules:

```console
#! shlx $1v, $2v, $3v -> shl $3v $2v $1v
#! shrx $1v, $2v, $3v -> split $3v dc $2v $1v
```

There is a problem in these rules. The `shl` and
`split` commands only allow constant shifting and splitting. We
need to change the variable `$1v` to a constant. After
examining `ecp_nistz256_mul_mont`, we see the first argument of all `shlx`
and `shrx` instructions is always `%r14`. Moreover,
`%r14` is set to `$0x20` and never changed. We can ask
$\cryptoline$ to check the value of `$1v` is always 32 and then
use 32 as the shifting and splitting constant. The $\cryptoline$
`assert P && Q` command checks both
`P and Q` must be true. The
verification fails if any of `P` or
`Q` can be false. Consider the following rules:

```console
#! shlx $1v, $2v, $3v -> assert $1v=32 && true;\nshl $3v $2v 32
#! shrx $1v, $2v, $3v -> assert $1v=32 && true;\nsplit $3v dc $2v 32
```

The `assert $1v=32 && true` command ensures `$1v`
must be 32 at this location. If so, we use the constant 32 instead of
the variable `$1v`. Note that we ask an external CAS to check
if `$1v` is equal 32. If you would like to use the SMT-based
engine, use `assert true && $1v=32@64` instead.

The translation rule for `shlx` neverthelss would not
work. Safety conditions would fail during verification if they were
used. To explain what safety conditions are, recall that $\cryptoline$
employs two different engines. Every $\cryptoline$ command therefore has
two different interpretations: one for the SMT-based, the other for
the CAS-base engine. The `shl d s c`
command is interpreted as the logical left shift in bit-vector theory
in the SMT-based engine. It is interpreted by the equation
$\textit{d} = \texttt{\textit{s}} \times 2^{\textit{c}}$
in the CAS-based engine. Two different
interpretations need to be related, otherwise their results may differ
unexpectedly. To relate both interpretations of `shl`,
$\cryptoline$ checks safety conditions to see if information
might be lost in the command. For `shl`, the safety condition
is that only zeros are shifted out. Thus both interpretations
coincide. In `ecp_nistz256_mul_mont`, this is not the case. We need to translate the
$\xeightysix$ `shlx` instruction differently to avoid the safety
condition failure.

Let us go back to `ecp_nistz256_mul_mont.gas`. Consider the following rule for
`shlx`:

```console
#! shlx $1v, $2v, $3v -> assert $1v=32 && true;\nsplit ddc $3v $2v 32;\nshl $3v $3v 32
```

After check `$1v` is 32, it splits `$2v` into two. The
high 32-bit value is stored in `ddc`. The low 32-bit value in
`$2v` is then shifted to the left by 32 bits.

To further improve our translation rules, let us see how `shlx`
and `shrx` are used in `ecp_nistz256_mul_mont.gas`:

```console
shlx   %r14,%r8,%rbp              #! PC = 0x55555557d72e
adc    %rcx,%r11                  #! PC = 0x55555557d733
shrx   %r14,%r8,%rcx              #! PC = 0x55555557d736
```

The `shlx` instruction puts the low 32-bit of `r8` in
`rbp`. Then `shrx` puts the high 32-bit of `r8`
in `rcx`. In the $\cryptoline$ fragment, the variable
`ddc` is in fact equal to `rcx`. Let us change the rule
for `shrx` to check it. Consider the following rule:

```console
#! shrx $1v, $2v, $3v -> assert $1v=32 && true;\nsplit $3v dc $2v 32;\nassert true && $3v=ddc;\nassume $3v=ddc && true
```

After obtaining `$3v`, the new rule asks the SMT-based engine
to check if `$3v` is equal to `ddc`. The equation is
then passed to the CAS-based engine by the $\cryptoline$ `assume`
command. This is a common technique to pass information between
engines. We ask one engine to verify a property with `assert`,
and then pass the property to the other engine with `assume`.

We are ready to apply the translation rules. After commenting out
irrelevant instructions in trace, use the following command:

```bash
$ $CL_HOME/scripts/to_zdsl.py ecp_nistz256_mul_mont.gas > ecp_nistz256_mul_mont.cl
```

It remains to declare input parameters and specify properties about
`ecp_nistz256_mul_mont`. The declaration and pre-condition are similar to `ecp_nistz256_add`:

```console
proc main (uint64 a0, uint64 a1, uint64 a2, uint64 a3,
           uint64 b0, uint64 b1, uint64 b2, uint64 b3,
           uint64 m0, uint64 m1, uint64 m2, uint64 m3) =
{
  and [ m0 = 0xffffffffffffffff, m1 = 0x00000000ffffffff,
        m2 = 0x0000000000000000, m3 = 0xffffffff00000001 ]
  &&
  and [ m0 = 0xffffffffffffffff@64, m1 = 0x00000000ffffffff@64,
        m2 = 0x0000000000000000@64, m3 = 0xffffffff00000001@64,
        limbs 64 [a0, a1, a2, a3] <u limbs 64 [m0, m1, m2, m3],
        limbs 64 [b0, b1, b2, b3] <u limbs 64 [m0, m1, m2, m3]
  ]
}
```

Note that the modulo `m`'s appear in both parts of
pre-condition. Since we will use the CAS-based engine, we need to tell
the engine about `m`'s. Simiarly, we initialize memory stores
with input parameters and constants.

```console
mov L0x7fffffffd9b0 a0; mov L0x7fffffffd9b8 a1;
mov L0x7fffffffd9c0 a2; mov L0x7fffffffd9c8 a3;

mov L0x7fffffffd9d0 b0; mov L0x7fffffffd9d8 b1;
mov L0x7fffffffd9e0 b2; mov L0x7fffffffd9e8 b3;

mov L0x55555557c000 0xffffffffffffffff@uint64;
mov L0x55555557c008 0x00000000ffffffff@uint64;
mov L0x55555557c010 0x0000000000000000@uint64;
mov L0x55555557c018 0xffffffff00000001@uint64;
```

At the end of `ecp_nistz256_mul_mont.cl`, the results `c`'s are obtained from
memory stores.

```console
mov c0 L0x7fffffffd9f0; mov c1 L0x7fffffffd9f8;
mov c2 L0x7fffffffda00; mov c3 L0x7fffffffda08;
```

And we use the following post-condition:

```console
{
  eqmod limbs 64 [0, 0, 0, 0, c0, c1, c2, c3]
        limbs 64 [a0, a1, a2, a3] * limbs 64 [b0, b1, b2, b3]
        limbs 64 [m0, m1, m2, m3]
&&
  limbs 64 [c0, c1, c2, c3] <u limbs 64 [m0, m1, m2, m3]
}
```

In the post-condition, we ask the CAS-based engine to verify
$c \times 2^{256} \equiv a \times b \mod p256$.
For the range check $c < p256$,
we employs the SMT-based engine.

#### Verification

We are ready to verify our model. Type

```bash
$ $CL_HOME/cv.exe -v -isafety ecp_nistz256_mul_mont.cl
```

$\cryptoline$ reports the algebraic specification fails. We will add
more annotations to our model. We have seen how information can be
passed between engines in the translation rules for `shlx` and
`shrx`. Another useful information to pass from the SMT-based
to the CAS-based
engines is addition carries. When carries propogate along long
additions, the last carry is almost always zero. Such information is
easily inferred with the SMT-based engine. In `ecp_nistz256_mul_mont`, two threads
of long additions are computed interleavingly. One uses the
$\xeightysix$ `adcx` instruction and the other uses
`adox`. There are three pairs of interleaving long
additions. At the end of each pair, we annotate `ecp_nistz256_mul_mont.cl` with the
following commands:

```console
(* NOTE: can't carry *)
assert true && and [carry=0@1,overflow=0@1];
assume and [carry=0,overflow=0] && true;
```

Here, we ask the SMT-based engine to verify both carry and overflow
are zeros, and then pass the information to the CAS-baesd engine.

The last annotation we need to add is for the conditional moves at the
end of `ecp_nistz256_mul_mont`. Similar to `ecp_nistz256_add`, the conditional moves check if
the Montgomery product is less than $p256$ by subtraction. If not, the
difference is returned. The SMT-based engine suffices to verify this
in `ecp_nistz256_add`. We will verify the conditional moves in the SMT-based
engine and pass the information to the CAS-based engine. Let us save
the Montgomery product before subtraction with the following:

```console
ghost r12o@uint64, r13o@uint64, r8o@uint64, r9o@uint64, r10o@uint64 :
      and [r12o=r12, r13o=r13, r8o=r8, r9o=r9, r10o=r10]
   && and [r12o=r12, r13o=r13, r8o=r8, r9o=r9, r10o=r10];
```

The keyword `ghost` declares five reference variables
`r12o`, `r13o`, `r8o`, `r9o`, and
`r10o`. These reference variables can only appear in
`assert` and `assume` commands and hence cannot the
computation of `ecp_nistz256_mul_mont`. After the conditional moves, we add two
$\cryptoline$ commands:

```console
(* NOTE: final reduction *)
assert true &&
       eqmod limbs 64 [r12, r13, r8, r9, 0@64]
             limbs 64 [r12o, r13o, r8o, r9o, r10o]
             limbs 64 [m0, m1, m2, m3, 0@64];
assume eqmod limbs 64 [r12, r13, r8, r9, 0]
             limbs 64 [r12o, r13o, r8o, r9o, r10o]
             limbs 64 [m0, m1, m2, m3, 0] && true;
```

The `assert` command asks the SMT-based engine to verify the
result is congruent to the Montgomery product modulo $p256$. The
information is then passed to the CAS-based engine in
`assume`.

Using the following command, $\cryptoline$ reports `ecp_nistz256_mul_mont`
is verified:

```bash
$ $CL_HOME/cv.exe -v -isafety ecp_nistz256_mul_mont.cl
```

**Exercise:** Construct a model for `ecp_nistz256_sqr_mont` in
`ecp_nistz256-x86_64.pl` and verify it.

### Compositional Reasoning with `cut`

The `ecp_nistz256_mul_mont` subroutine computes in two phases. The first phase
computes the Montgomery product and stores it in five registers
`r12`, `r13`, `r8`, `r9`, and
`r10`. The second phase reduces the Montgomery product by
modulo $p256$ and stores the final result in four registers
`r12`, `r13`, `r8`, and `r9`. Since the
two phases appear to be independent, they may be verified
independently.

The $\cryptoline$ `cut P && Q` command
provides a simple mechanism to divide a verification task by
parts. Consider the $\cryptoline$ model in
"Original". The `cut` command effectively
splits the model into three parts shown in "Part I" to
"Part III". Observe that `P1 && Q1` is the
post-condition in "Part I" but the pre-condition in
"Part II". Similarly, `P2 && Q2` is the
post-condition in "Part II" but the pre-condition in
"Part III". $\cryptoline$ reports successful
verification when all three parts are verified successfully.
Informally, `P1 && Q1` is established and then assumed to
verify `P2 && Q2`. `P2 && Q2` is then assumed to
prove `P3 && Q3`. If we know how to divide a large
cryptographic prgram into phases, the `cut` command allows us
to verify the program by parts.

{{< columns >}}

Original:
```console
proc main (...) =
{ P0 && Q0 }
(* Phase I *)
cut P1 && Q1;
(* Phase II *)
cut P2 && Q2:
(* Phase III *)
{ P3 && Q3 }
```

<--->

Part I:
```console
proc main0 (...) =
{ P0 && Q0 }
(* Phase I *)
{ P1 && Q1 }
```

<--->

Part II:
```console
proc main1 (...) =
{ P1 && Q1 }
(* Phase II *)
{ P2 && Q2 }
```

<--->

Part III:
```console
proc main2 (...) =
{ P2 && Q2 }
(* Phase III *)
{ P3 && Q3 }
```

{{< /columns >}}

Back to `ecp_nistz256_mul_mont`, it is natural to divide the subroutine by its two
phases. Let us add the following command just before the
`ghost` declaration:

```console
cut eqmod limbs 64 [0, 0, 0, 0, r12, r13, r8, r9, r10]
          (limbs 64 [a0, a1, a2, a3] * limbs 64 [b0, b1, b2, b3])
          limbs 64 [m0, m1, m2, m3] &&
    and [limbs 64 [r12, r13, r8, r9, r10] <u
         2@320 * limbs 64 [m0, m1, m2, m3, 0@64],
         m0 = 0xffffffffffffffff@64, m1 = 0x00000000ffffffff@64,
         m2 = 0x0000000000000000@64, m3 = 0xffffffff00000001@64,
         r14=0x00000000ffffffff@64, r15=0xffffffff00000001@64,
         r12=rbx, r13=rdx];
```

The `cut` command states the Montgomery product is stored in
the five registers `r12`, `r13`, `r8`,
`r9`, and `r10` and the product is less than twice of
the modulo. The remaining equations collect necessary assumptions to
verify the reduction modulo $p256$.

With the simple modification, we can verify `ecp_nistz256_mul_mont.cl` again:

```bash
$ $CL_HOME/cv.exe -v -isafety ecp_nistz256_mul_mont.cl
```

On Raspberry Pi 4 (1.8GHz ARM Cortex-A72 with 8GB RAM), the model
without `cut` is verified in 153 seconds. In contrast, the
model with `cut` is verified in 52 seconds. The `cut`
command can significantly reduce the verification time if used
propertly.

**Exercise:** Add `cut` to your model for
`ecp_nistz256_sqr_mont` and compare verification time.