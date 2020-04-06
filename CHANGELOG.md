<a name="9.1.0"></a>
# [9.1.0](https://github.com/angular/angular/compare/9.0.0...9.1.0) (2020-03-25)

### Release Highlights

* TypeScript 3.8 update
* ngcc improvements
  * performance optimizations
  * concurrency & reliability improvements for monorepo use-cases (npm postinstall script no longer recommended)
* i18n now supports RTL locale info
* Ivy compatibility fixes


### Features

* **bazel:** enable ivy template type-checking in g3 ([#35672](https://github.com/angular/angular/issues/35672)) ([8f5b7f3](https://github.com/angular/angular/commit/8f5b7f3))


### Performance Improvements

* **core:** add micro benchmark for destroy hook invocation ([#35784](https://github.com/angular/angular/issues/35784)) ([0653db1](https://github.com/angular/angular/commit/0653db1))


### Bug Fixes

* **animations:** Remove ɵAnimationDriver from private exports ([#35690](https://github.com/angular/angular/issues/35690)) ([ec789b0](https://github.com/angular/angular/commit/ec789b0))
