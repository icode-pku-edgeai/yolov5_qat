Generator Operators
###################

Generators provide a way to generate data on-the-fly without a tensor view as input. They are typically lower overhead than other operator types
since their only purpose is to compute a single value at a particular location based on various inputs.

.. doxygenfunction:: matx::zeros(ShapeType &&s)
.. doxygenfunction:: matx::zeros(const index_t (&s)[RANK])
.. doxygenfunction:: matx::ones(ShapeType &&s)
.. doxygenfunction:: matx::ones(const index_t (&s)[RANK])
.. doxygenfunction:: matx::eye(ShapeType &&s)
.. doxygenfunction:: matx::eye(const index_t (&s)[RANK])
.. doxygenfunction:: matx::diag(ShapeType &&s, T val))
.. doxygenfunction:: matx::diag(const index_t (&s)[RANK], T val))
.. doxygenfunction:: matx::alternate(ShapeType &&s)
.. doxygenfunction:: matx::alternate(const index_t (&s)[RANK])
.. doxygenfunction:: matx::hamming(ShapeType &&s)
.. doxygenfunction:: matx::hamming(const index_t (&s)[RANK])
.. doxygenfunction:: matx::hanning(ShapeType &&s)
.. doxygenfunction:: matx::hanning(const index_t (&s)[RANK])
.. doxygenfunction:: matx::bartlett(ShapeType &&s)
.. doxygenfunction:: matx::bartlett(const index_t (&s)[RANK])
.. doxygenfunction:: matx::blackman(ShapeType &&s)
.. doxygenfunction:: matx::blackman(const index_t (&s)[RANK])
.. doxygenfunction:: matx::flattop(ShapeType &&s)
.. doxygenfunction:: matx::flattop(const index_t (&s)[RANK])
.. doxygenfunction:: matx::range(ShapeType &&s, T first, T step)
.. doxygenfunction:: matx::range(const index_t (&s)[RANK], T first, T step)
.. doxygenfunction:: matx::linspace(ShapeType &&s, T first, T last)
.. doxygenfunction:: matx::linspace(const index_t (&s)[RANK], T first, T last)
.. doxygenfunction:: matx::logspace(ShapeType &&s, T first, T last)
.. doxygenfunction:: matx::logspace(const index_t (&s)[RANK], T first, T last)
.. doxygenfunction:: matx::fftfreq(index_t n, float d = 1.0)
.. doxygenfunction:: matx::meshgrid(Ts&&... ts)
.. doxygenfunction:: matx::chirp(SpaceOp t, FreqType f0, typename SpaceOp::scalar_type t1, FreqType f1, ChirpMethod method )
.. doxygenfunction:: matx::chirp(index_t num, TimeType last, FreqType f0, TimeType t1, FreqType f1, ChirpMethod method)
.. doxygenfunction:: matx::cchirp(SpaceOp t, FreqType f0, typename SpaceOp::scalar_type t1, FreqType f1, ChirpMethod method)
.. doxygenfunction:: matx::cchirp(index_t num, TimeType last, FreqType f0, TimeType t1, FreqType f1, ChirpMethod method)
