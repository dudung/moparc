# mech
mechanics

```mermaid
flowchart LR
  %% links
  mech --- poin & sysp & cont
  poin --- kine & dyne
  sysp --- rigi
  cont --- soli & flui
  flui --- liqu & gase
  %% elements
  mech(( Mechanics ))
    poin(( Point<br>Particle ))
      kine(( Kinematics ))
      dyne(( Dynamics ))
    sysp(( System of<br>Particles ))
      rigi(( Rigid<br>Body ))
    cont(( Continuum<br>Mechanics ))
      soli(( Solid ))
      flui(( Fluid ))
        liqu(( Liquid ))
        gase(( Gas ))
  %% pages
  click mech "https://github.com/dudung/moparc/tree/main/maps/phys" _self
  %% styles
  classDef prev fill:#afa,stroke:#090,stroke-width:1px,color:#090;
  classDef next fill:#ccf,stroke:#009,stroke-width:1px,color:#009;
  class mech prev;
```

## refs
1. Robert A LaBudde, Donald Greenspan, "Discrete mechanics—A general treatment", Jurnal of Computational Physics [J Comput Phys], vol 15, no 2, p 134-167, Jun 1974, url <https://doi.org/10.1016/0021-9991(74)90081-3>.
2. Wei-qiu Chen, "The renaissance of continuum mechanics", Journal of Zhejiang University SCIENCE A [ J Zheijang Univ-Sci],  vol 15, no, p 231–240,  Apr 2014, url <https://doi.org/10.1631/jzus.A1400079>.
3. Olaf Etzmuss, Joachim Gross, Wolfgang Strasser, "Deriving a particle system from continuum mechanics for the animation of deformable objects," IEEE Transactions on Visualization and Computer Graphics [IEEE Trans Vis Comput Graph], vol 9, no 4, p 538-550, Oct-Dec 2003, url <https://doi.org/10.1109/TVCG.2003.1260747>.