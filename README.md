# [Bisect_ppx][bisect] + esy starter repo

```
git clone https://github.com/aantron/bisect-starter-esy.git
cd bisect-starter-esy
esy install

esy dune runtest --instrument-with bisect_ppx --force
esy bisect-ppx-report html
```

These commands generate
[this coverage report](https://aantron.github.io/bisect-starter-esy/) locally
in the `_coverage/` directory. Use your browser to open `_coverage/index.html`!

[Here][demo] is an example of a coverage report for a real-world project.

See [aantron/bisect_ppx][bisect], especially the [esy
instructions][esy-instructions].

[bisect]: https://github.com/aantron/bisect_ppx
[esy-instructions]: https://github.com/aantron/bisect_ppx#esy
[demo]: https://aantron.github.io/bisect_ppx/demo/
