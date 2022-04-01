# decryptor
Decrypt codebase (planning stub).

# Description
If there's a turing-complete program byte array, we can redefine them as simple pmpu mnemonic set on finite memory finite register computer. (simple pmpu is also turing-complete.)
So with maximum set of operators and some status condition, we can approximate non general protection fault mnemonic set from byte array without caching nor so on if input is pure function and/or call/in/out to external space.

We target input argument as mnemonic set size, extra cpu inner status size, possible memory range relative/absolute, then, we want to get possible mnemonic set array.
But it is so far from the bases we have now.

# Tips
If the computer is infected compete with unknown mnemonic virtual machine codeset, the compiler/base binary needs to hook i/o or implant the codebase into them. If so, the binary infected needs this implementation, without this, if we have compiling source and extra new language source, the binary implant needs to read what the code means in compiler source, they're worse difficult than this.
