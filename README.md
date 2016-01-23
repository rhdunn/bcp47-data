# BCP 47 Data

This project is a collection of data files useful for working with BCP 47
language tags.

The IANA Language Subtag Registry and other data sets are mirrored here to
provide stable versions for specific builds of projects and generated data
sets derived from these data files.

| File | Modified | Description |
|------|----------|-------------|
| [language-subtag-registry](language-subtag-registry) | 2016-01-10 | The [IANA Language Subtag Registry](http://www.iana.org/assignments/language-subtag-registry/language-subtag-registry). |
| [accents](accents) | 2014-10-08 | Private use BCP47/RFC4646/RFC5646 extensions for describing accents and dialects. |

Additionally, the [relationships](relationships) directory contains data that
relates language codes together according to which language family they belong.
These files have line comments that start with the `#` character. The other
lines have the following format:

	TYPE:CODE:PARENT

where `TYPE` can be:

*  `h` for hierarchical relationships of the ISO 639-5 language family subtags.

## License

The IANA Language Subtag Registry is part of the BCP 47/RFC 5646 standard.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.
