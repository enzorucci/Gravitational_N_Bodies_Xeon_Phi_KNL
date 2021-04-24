# Gravitational N bodies simulation on Intel’s Architectures Based on AVX-512 Instruction Set

Incremental optimizations of direct N body algorithm for Intel architectures based on AVX-512 instruction set. This SIMD set was initially supported by Intel’s Xeon Phi Knights Landing (KNL) manycore processors launched at 2016. Recently, it has been included in Intel’s general-purpose processors too, starting at the Skylake (SKL) server microarchitecture and now in its successor Cascade Lake (CKL).

## Usage

  ```
  ./optX.exe N S T
  --
  N is the number of bodies
  S is the number of steps
  T is the number of threads

```
## Build

Remember that performance depends on the BLOCKSIZE constant. Tune BLOCKSIZE according to your system.

## References

This implementation is the base for the following publications. Please, cite accordingly:

Rucci E., Moreno E., Pousa A., Chichizola F. (2020) Optimization of the N-Body Simulation on Intel’s Architectures Based on AVX-512 Instruction Set. In: Pesado P., Arroyo M. (eds) Computer Science – CACIC 2019. CACIC 2019. Communications in Computer and Information Science, vol 1184. Springer, Cham. [https://doi.org/10.1007/978-3-030-48325-8_3](https://link.springer.com/chapter/10.1007/978-3-030-48325-8_3)

Rucci E., Moreno E., Pousa A., Chichizola F. (2019) Simulación de N Cuerpos Computacionales sobre Intel Xeon Phi KNL. In: Actas del XXV Congreso Argentino de Ciencias de la Computación (CACIC 2019). Universidad Nacional de Río Cuarto, 14 al 18 de octubre de 2019. [http://sedici.unlp.edu.ar/handle/10915/90463](http://sedici.unlp.edu.ar/handle/10915/90463)




Disclaimer: *The files uploaded in this repository are subject to modifications and might differ slightly from what's presented in the publications*.
