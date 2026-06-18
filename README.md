
# LionKey: NFC Extension

Bachelor's thesis at [CTU FEE][FEL] focused on extending the [LionKey] FIDO2 security key with NFC functionality. Successfully defended (grade **A**). 

> [!IMPORTANT]
> The source code of the implementation is available at [Matesin/lionkey-nfc][Repo]

> [!IMPORTANT]
> The LionKey project was started by Ing. Martin Endler as a part of his master's thesis. To find out more, you can visit:
> [pokusew/fel-masters-thesis][Endler Thesis]
> [pokusew/lionkey][LionKey Repo]

## Abstract

The thesis investigates the integration of Near Field Communication (NFC) into the LionKey hardware security key and describes the design, implementation, and evaluation of NFC support for FIDO2 authentication.

The work covers:

- FIDO2 and passkeys (briefly)
- NFC technology and protocols
- Implementation (HW & SW)
- Testing and evaluation

## Repository Structure

```text
.
├── tex/                        # Thesis source files
├── images/                     # Images and diagrams
├── files/                      # Declaration and Thesis Assignment
├── LionKey_NFC_Support.pdf     # Latest PDF Export
└── README.md
```
## Results

The thesis extends LionKey with NFC functionality and demonstrates the feasibility of FIDO2 authentication over NFC. The implementation includes:

- NFC transport support
- CTAP communication over NFC
- NDEF record support
- Integration into the existing LionKey architecture
- Functional and interoperability testing

## Citation
If you use or reference this work, please cite the corresponding bachelor's thesis.

```bibtex
@bachelorsthesis {martan2026lionkey,
  author = {Matyáš Martan},
  title = {LionKey -- NFC Extension},
  school = {Czech Technical University in Prague},
  year = {2026},
  type = {Bachelor's Thesis}
}
```

<!-- links  -->
[Repo]: https://github.com/Matesin/lionkey-nfc
[LionKey Repo]: https://github.com/pokusew/lionkey
[Endler Thesis]: https://github.com/pokusew/fel-masters-thesis
[FEL]: https://fel.cvut.cz/en
[LionKey]: https://lionkey.dev
