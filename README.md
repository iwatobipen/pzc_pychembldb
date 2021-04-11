# pzc_pychembldb

- modified version of pzc

## original repository

- https://github.com/pzc/rdkit/tree/master/Contrib/pzc

## requirements

- pychembldb(https://pypi.org/project/pychembldb/)
- postgres server of ChEMBLDB

## Basic usage

- make model
- Following command make predictive model of given accession number.
- After training model, you can view summary table.

 ```
 $ python p_con_pychembldb.py accession=P43088 -unique
 ```
