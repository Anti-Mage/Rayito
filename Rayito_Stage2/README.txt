Stage 2:

Everything in stage 1, plus the following changes...

* Light shape subclass, with (double-sided) rectangle area light subclass
* Method to find the lights in a scene
* Shape sampling method to find a random point on a shape (used for lights currently)
* Emission added to intersection results
* Infinite plane has a procedural bullseye texture option
* Multiple samples per pixel supported (antialiasing)
* Fast random number stream added
* Shadow rays cast
* Simple Lambertian diffuse shading


Stage 1:

* Math support: RGB colors, 3D vectors/points, ray definition
* Scene graph: abstract shape base class with ray intersectio method, infinite plane subclass
* Camera ray construction
* Single-sample-per-pixel ray-traced image

