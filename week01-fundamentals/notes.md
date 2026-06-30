-- Notes found when studying, useful when coming back for reference.

- Primary Keys: Can be made up of either 'Natural' or 'Surrogate' keys.
  - Natural key: a unique identifier based on real-world data already in the row, i.e. email address, ISBN.
  - Surrogate key: an artificially generated identifier with no business meaning (e.g. auto-incrementing integer), used to avoid the natural key's value changing and breaking foreign key references elsewhere in the db. Also avoids cases where a "natural" key turns out not to be as unique as assumed (e.g. duplicate names).

- Normalization: going through 1NF → 3NF to eliminate redundant data and 
  minimise update anomalies, by ensuring data isn't duplicated across rows/tables.
  - 1NF: values must be atomic (one indivisible value per column, no lists 
    crammed into one cell) and have sensible naming conventions.
  - 2NF: no partial dependency — only relevant with composite keys, 
    means every non-key column must depend on the WHOLE key, not just part of it.
  - 3NF: no transitive dependency — a non-key column shouldn't depend on 
    another non-key column instead of depending on the key directly.

  Note: "atomicity" here (1NF) is different from transaction atomicity 
  (the 'A' in ACID) — that's about a transaction fully completing or fully 
  rolling back, not about column values. Same word, different concept.