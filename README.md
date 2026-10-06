# Li-Sulphur_batteries

The calculations suggest that SPN is readily lithiated before polysulfide reduction, but LiSPN is not thermodynamically capable of directly reducing isolated polysulfides; its beneficial role is therefore more likely associated with Li/polysulfide coordination, stabilization, or reaction kinetics.


# Li–S / SPN Reaction Energies

Electronic energies and reaction energies for the Li–S polysulfide series and
the SPN/LiSPN redox couple.

## Calculated species

| Species | Formula | Energy (Eh) |
|---|---|---:|
| Li20S10 | Li20S10 | -4134.8720702294 |
| Li2S | Li2S | -413.3810835382 |
| Li2S2 | Li2S2 | -811.6401743426 |
| Li2S4 | Li2S4 | -1608.1312850002 |
| Li2S6 | Li2S6 | -2404.5934191652 |
| Li2S8 | Li2S8 | -3201.0304961873 |
| LiSPN | C6H4F5LiNO2S | -1341.6927449905 |
| SPN | C6H4F5NO2S | -1334.0874866311 |

## Reaction energies

| Reaction | ΔE (eV) |
|---|---:|
| Li2S6 + 2e + 2Li → Li2S4 + Li2S2 | -413.0155 |
| Li2S4 + 2e + 2Li → 2Li2S2 | -412.2270 |
| Li2S2 + 2e + 2Li → 2Li2S | -411.4904 |
| Li2S6 + Li2S2 → 2Li2S4 | -0.7885 |
| 2Li2S4 → Li2S6 + Li2S2 | +0.7885 |
| SPN + e + Li → LiSPN | -206.9496 |
| 2LiSPN + Li2S6 → 2SPN + Li2S4 + Li2S2 | +0.8837 |
| 2LiSPN + Li2S4 → 2SPN + 2Li2S2 | +1.6722 |
| 2LiSPN + Li2S2 → 2SPN + 2Li2S | +2.4089 |

## Relative redox scale

The reaction

    Li2S6 + 2e + 2Li → Li2S4 + Li2S2

is used as the zero of the relative voltage scale.

| Ucross (V) | Reaction |
|---:|---|
| +0.4419 | SPN + e + Li → LiSPN |
| 0.0000 | Li2S6 + 2e + 2Li → Li2S4 + Li2S2 |
| -0.3942 | Li2S4 + 2e + 2Li → 2Li2S2 |
| -0.7626 | Li2S2 + 2e + 2Li → 2Li2S |

## Key for interpretation

**ΔE:** Electronic reaction energy calculated from the molecular energies.
Negative values indicate an energetically favorable reaction in the written
direction; positive values indicate an unfavorable reaction.

**Ucross:** Relative potential at which a Li/e reduction reaction is
thermoneutral. The Li2S6 reduction is arbitrarily assigned U = 0 V, so these
are relative rather than absolute voltages vs. Li/Li+.

At potentials **below Ucross**, the corresponding reduction becomes
energetically favorable within this convention.

The SPN/LiSPN couple lies **+0.442 V above** the Li2S6 reduction. Thus SPN is
reduced to LiSPN before the polysulfide reduction sequence on lowering the
potential.

The direct LiSPN-mediated reactions are all uphill:

    Li2S6 : +0.884 eV
    Li2S4 : +1.672 eV
    Li2S2 : +2.409 eV

Thus, for the isolated species considered here, LiSPN is not predicted to
reduce the polysulfides spontaneously. Any mediator effect of SPN may instead
involve complex formation, structural stabilization, kinetics, or other
reaction pathways not represented by these isolated-species energies.

## Notes

- Energies are electronic energies; thermal, entropic, concentration and
  solid-state corrections are not included.
- The voltage scale is relative and should not be interpreted directly as
  voltage vs. Li/Li+ without an absolute reference.
- `Li` and `e` in the reactions represent transfer of a Li+/electron pair
  from the electrochemical reservoir.
