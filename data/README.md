# Variable Ordering Data Explained

## MetiTarski Datasets

The dataset are predominantly gathered from `MetiTarski`, by logging MetiTarski's RCF subproblem queries during its proof search as part of MetiTarski RCF proof strategy development and evaluation [Passmore, 2012]. Inspired by England et al. [England, 2019], the performance data considering the different variable orderings was gathered by running the Maple RegularChains CAD implementation against all variable permutations.

### Raw Data Location

* [./raw/metitarski/](./raw/metitarski/)
* [./raw/metitarski/original](./raw/metitarski/original)
* [./raw/metitarski/balanced](./raw/metitarski/balanced)

### Processed Data Location

* [./processed/metitarski/metitarski_original_processed.csv](./processed/metitarski/metitarski_original_processed.csv)
  - Produced via running: `python scripts/process_metitarski_data.py --dataset original`
* [./processed/metitarski/metitarski_balanced_processed.csv](./processed/metitarski/metitarski_balanced_processed.csv)
  - Produced via running: `python scripts/process_metitarski_data.py --dataset balanced`

## References

* `[England, 2019]` England, Matthew, and Dorian Florescu. "Comparing machine learning models to choose the variable ordering for cylindrical algebraic decomposition." International Conference on Intelligent Computer Mathematics. Springer, Cham, 2019.
* `[Passmore, 2012]` Passmore, Grant Olney, Lawrence C. Paulson, and Leonardo De Moura. "Real algebraic strategies for MetiTarski proofs." International Conference on Intelligent Computer Mathematics. Springer, Berlin, Heidelberg, 2012.
