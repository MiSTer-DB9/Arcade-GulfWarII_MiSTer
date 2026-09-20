# IKA32010 provenance

- Upstream: <https://github.com/ika-musume/IKA32010>
- Commit: `51bc1f05a2a08a61c8815a9643d08a42e99779c6`
- License: BSD-2-Clause; see `LICENSE`

`IKA32010.sv`, `IKA32010_disasm.sv`, and `IKA32010_mnemonics.sv` were copied
from that revision. Local changes make the disassembly defines opt-in through
`IKA32010_ENABLE_DISASSEMBLY` and correct the inverted active-low reset test for
the data-page register. `sim/ika32010_dp_tb.sv` verifies that `LDPK 1` leaves
the data-page register set.
