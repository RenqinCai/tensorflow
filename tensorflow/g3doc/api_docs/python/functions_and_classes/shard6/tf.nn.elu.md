### `tf.nn.elu(features, name=None)` {#elu}

Computes exponential linear: `exp(features) - 1` if < 0, `features` otherwise.

See [Fast and Accurate Deep Network Learning by Exponential Linear Units (ELUs)
](http://arxiv.org/abs/1511.07289)

##### Args:


*  <b>`features`</b>: A `Output`. Must be one of the following types: `float32`, `float64`, `int32`, `int64`, `uint8`, `int16`, `int8`, `uint16`, `half`.
*  <b>`name`</b>: A name for the operation (optional).

##### Returns:

  A `Output`. Has the same type as `features`.

