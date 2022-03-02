# Nifti.NET // Unity compatible fork
A basic library for reading, writing and manipulating NIfTI files.

(If you're looking for the TensorFlow CNN platform, try NiftyNet (https://niftynet.io/))

## Unity compatability

This fork has a statically typed (instead of using dynamic) code path for use in unity with AOT compilation.

Use `ReadTyped<Type>(...)` instead of `Read(...)`. Type can be inferred from reading the header first.

Writing is not adjusted and will not work.
