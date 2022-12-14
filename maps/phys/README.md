# phys
physics

```mermaid
flowchart LR
  %% links
  phys --- clas & mode
  clas --- elem & mech & ther
  mode --- rela & quan --- qfth
  mech & ther --- stat
  quan ---- stat
  %% elements
  phys(( Physics ))
  clas(( Classical<br>Physisc ))
    mech(( Mechanics ))
    ther(( Thermo-<br>dynamics ))
    elem(( Electro-<br>magnetism ))
  mode(( Modern<br>Physics ))
    rela(( Relativity ))
    quan(( Quantum<br>Mechanics ))
    qfth(( Quantum<br>Field<br>Theory))
  stat(( Statistical<br>Mechanics ))
  %% pages
  click phys "https://github.com/dudung/moparc/tree/main/maps//README.md" _self
  click mech "https://github.com/dudung/moparc/tree/main/maps/phys/mech//README.md" _self
  %% styles
  classDef default fill:#fff,stroke:#999,stroke-width:1px,color:#999;
  classDef prev fill:#fcc,stroke:#900,stroke-width:1px,color:#900;
  classDef next fill:#afa,stroke:#090,stroke-width:1px,color:#090;
  class phys prev;
  class mech next;
```

## refs
1. Robert A LaBudde, Donald Greenspan, "Discrete mechanics—A general treatment", Jurnal of Computational Physics [J Comput Phys], vol 15, no 2, p 134-167, Jun 1974, url <https://doi.org/10.1016/0021-9991(74)90081-3>.
2. Wei-qiu Chen, "The renaissance of continuum mechanics", Journal of Zhejiang University SCIENCE A [ J Zheijang Univ-Sci],  vol 15, no, p 231–240,  Apr 2014, url <https://doi.org/10.1631/jzus.A1400079>.