-- Notes found when studying, useful when coming back for reference.

- Primary Keys: Can be made up of either 'Natural' or 'Surrogate' keys.
  - Natural key: a unique identifier based on real-world data already in the row, i.e. email address, ISBN.
  - Surrogate key: an artificially generated identifier with no business meaning (e.g. auto-incrementing integer), used to avoid the natural key's value changing and breaking foreign key references elsewhere in the db. Also avoids cases where a "natural" key turns out not to be as unique as assumed (e.g. duplicate names).