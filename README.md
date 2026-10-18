# School maths skill names in 7 languages

473 school mathematics skills — from "add within 20" to "accumulated change from a rate" — named in English,
Polish, German, French, Spanish, Italian and Dutch the way **each country's curriculum and textbooks** name
the topic, not as a word-for-word translation: *Schriftliche Addition* in Germany, *addition posée* in France,
*cijferend optellen* in the Netherlands. Prepared by Imaginesis (https://imaginesis.com), a maths worksheet
generator that publishes worksheets in these seven languages.

Snapshot: 2026-10-18. License: Creative Commons Attribution 4.0 (CC BY 4.0) — cite as
"Imaginesis school maths skill names in 7 languages, 2026, https://doi.org/10.5281/zenodo.23452239".

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23452239.svg)](https://doi.org/10.5281/zenodo.23452239)

## Files

- `data/skill_names.csv` — `slug` (stable identifier, the same as in the curriculum crosswalk and the
  prerequisite graph), `level` (1 domain, 2 topic, 3 skill, 4 sub-skill), `parent_slug`, and `name_en`,
  `name_pl`, `name_de`, `name_fr`, `name_es`, `name_it`, `name_nl`.

## How the names were made — and how far to trust them

- **English and Polish** are the names used in the Imaginesis skills taxonomy, written and edited by people.
- **German, French, Spanish, Italian and Dutch are machine translations, then reviewed.** A local language model
  (Qwen3.6-35B-A3B) drafted each name with the instruction to use the school curriculum terminology of the
  country (Germany: KMK Bildungsstandards and Länder curricula; France: the cycle 2-4 and lycée programmes,
  Bulletin officiel 2024-2026; Spain: LOMLOE, Real Decreto 157/2022 and 217/2022; Italy: Indicazioni
  nazionali 2012/2025; the Netherlands: kerndoelen 2026 and the referentiekader rekenen). Every language was
  then reviewed in full, name by name, by a second model (Claude Sonnet) instructed to check that terminology,
  with those curriculum documents at hand for lookup; it mostly relied on its own knowledge of each school
  system and consulted the documents for doubtful terms. The review changed 104 (Italian) to 162 (French) of
  473 names — wrong maths terms (e.g. the Polish "Thales' theorem" is the German *Strahlensatz*), anglicisms,
  regional variants and words left in the wrong language. A random sample of 20 names per language was then
  read by the maintainer and a few more were corrected. Terminology varies between regions and textbook
  series (German Länder, Spanish autonomous communities, Dutch methods); the name given is a common one, not
  the only one.

Corrections from teachers are very welcome as GitHub issues.

## Related datasets

Curriculum crosswalk (where each skill sits in 10 national curricula): https://doi.org/10.5281/zenodo.23217841.
School notation and grade ages: https://doi.org/10.5281/zenodo.23451054. Skill prerequisite graph:
https://doi.org/10.5281/zenodo.23451451. Units of measurement and money: https://doi.org/10.5281/zenodo.23451760.
