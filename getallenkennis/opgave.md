# Hamming Opgave
#### Zijn de ontvangen hamming bits correct?

| 1  |  1 |  1 |  0 | 1  | 1  |  0 |
|---|---|---|---|---|---|---|
|  H1 |  H2 |  D3 |  H4 |  D5 | D6  | D7  |

*Oplossing*
Na het uitvoeren van een pariteitscontrole zien we dat H1 en H2 incorrect zijn.
> Aangezien hamming bit 1 en 2 verkeerd zijn dan weet je dat de fout ligt bij Databit 3
> de reeks ontvangen databits zou hier dus **0**110 moeten zijn i.p.v. 1110
