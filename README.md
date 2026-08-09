This repository contains two grammars, for Rust and Kotlin, both recently added in 2026. The intention is to eventually have all of the grammars here -- Java, Python, C\#, and whatever other ones become available. From the top-level
directory, you can build and test either grammar via:

```bash
  ant -f rust test
```
or:

```bash

  ant -f kotlin test
```

respectively. Note that the above is not currently working for any target language other than Java. This is also just an interim situation.