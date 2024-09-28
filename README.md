# SQuADDS Measured Data Staging Repository

This repository serves as a staging area for contributing measured device information to the [SQuADDS Database](https://huggingface.co/datasets/SQuADDS/SQuADDS_DB). It allows users to validate and submit new device entries, which will be reviewed and integrated into the official SQuADDS database upon approval.

## Citation

If you use the SQuADDS database in your research, please cite the following paper:

```
@article{Shanto2024squaddsvalidated,
  doi = {10.22331/q-2024-09-09-1465},
  url = {https://doi.org/10.22331/q-2024-09-09-1465},
  title = {{SQ}u{ADDS}: {A} validated design database and simulation workflow for superconducting qubit design},
  author = {Shanto, Sadman and Kuo, Andre and Miyamoto, Clark and Zhang, Haimeng and Maurya, Vivek and Vlachos, Evangelos and Hecht, Malida and Shum, Chung Wa and Levenson-Falk, Eli},
  journal = {{Quantum}},
  issn = {2521-327X},
  publisher = {{Verein zur F{\"{o}}rderung des Open Access Publizierens in den Quantenwissenschaften}},
  volume = {8},
  pages = {1465},
  month = sep,
  year = {2024}
}
```

---

## How to Contribute

We outline the contribution guidelines for SQuADDS in this [page](https://lfl-lab.github.io/SQuADDS/source/tutorials/Tutorial-3p5_Creating_a_new_dataset.html). Please read the guidelines before contributing to the SQuADDS project.

There are two ways to contribute to the SQuADDS Measured Data Staging Repository:

## GitHub Web Interface:

1. **Fork** the repository to your GitHub account.
2. **Clone** your forked repository locally.
3. Add your new entry to the `measured_device_database.json` file following the existing structure.
4. **Commit and push** your changes to your forked repository.
5. Create a **Pull Request** to this repository.

## SQuADDS API:

Follow [Tutorial 4: Contributing Experimentally-Validated Devices to the SQuADDS Database](https://lfl-lab.github.io/SQuADDS/source/tutorials/Tutorial_4_Contributing_Experimental_Data_to_SQuADDS.html)

---

### Related Links:

- **SQuADDS Documentation**: [https://lfl-lab.github.io/SQuADDS/](https://lfl-lab.github.io/SQuADDS/)
- **SQuADDS Python GitHub Repository**: [https://github.com/LFL-Lab/SQuADDS/](https://github.com/LFL-Lab/SQuADDS/)
- **SQuADDS Dataset on Hugging Face**: [https://huggingface.co/datasets/SQuADDS/SQuADDS_DB](https://huggingface.co/datasets/SQuADDS/SQuADDS_DB)
