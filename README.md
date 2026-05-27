# English-Persian Dictionary Dataset

This repository contains a cleaned English-to-Persian dictionary dataset with **300,000+** unique words & phrases, created by merging and refining several public resources.

It is designed to be a practical dataset for developers, students, researchers, and language-tool projects, rather than a perfect academic dictionary. Therefore, some entries may still need human review.

Included formats:
- `dictionary.csv`
- `dictionary.jsonl`
- `slices/by_letter/*.jsonl`
- `slices/by_chunk/*.jsonl`


## Dataset Statistics

| Metric | Count |
|---|---:|
| Total rows | 880,919 |
| Unique English headwords | 308,243 |
| Unique Persian translations | 601,052 |
| Entries with POS tags | 10,430 |
| Entries without POS tags | 870,489 |
| English/POS groups with multiple senses | 136,113 |
| Rows belonging to multi-sense groups | 702,526 |
| Letter slice files | 27 |
| Chunk slice files | 89 |


## Dataset Schema

| Field | Description |
|---|---|
| `english` | English word, phrase, idiom, or headword |
| `pos` | Normalized part-of-speech tag, if available |
| `sense_order` | Numeric order for separate meanings of the same English/POS group |
| `persian` | Persian equivalent |


## Resources Used

- [VahidN EnglishToPersianDictionaries](https://github.com/VahidN/EnglishToPersianDictionaries)
- [English-Persian Word Database](https://github.com/semnan-university-ai/English-Persian-Word-Database) 
- [English-Persian Computer Science Technical Dictionary](https://github.com/hkhojasteh/EN-FA-CS-Dictionary)
- [Wiktionary DSL Export](https://github.com/open-dsl-dict/wiktionary-dict)
- MHM Advance English-Persian Dictionary by Morteza Hajimahmoodzadeh


## License

This compiled dataset is based on multiple third-party resources with different licenses. Before using the dataset in commercial projects, please check the licenses of the upstream sources.
