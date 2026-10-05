::: mermaid
flowchart TD
A@{shape: hex, label : 'Nilai 80'} --> cekNilai{Lulus?}
cekNilai -->|Yes| C[OK]
cekNilai -->|No | D[End]
C --> E[DI HIRE FAANG]
D --> F[ULANG NEXT BATCH]
E --> TERIMA{TERIMA?}
TERIMA -->|Yes| I[GOOD]
TERIMA -->|No| H[SOMBONG]
:::
