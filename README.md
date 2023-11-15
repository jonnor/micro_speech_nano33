
Forked example of micro_speech from Tensorflow Lite Micro for the Arduino Nano 33.
Originally from [tflite-micro-arduino-examples](https://github.com/tensorflow/tflite-micro-arduino-examples/tree/main/examples/micro_speech).

Updated to work with the latest training code (as of November 2023),
so that one can deploy custom models.

Fixes issues such as

```
Didn't find op for builtin opcode 'CONV_2D' version '3'.
An older version of this builtin might be supported. Are you using an old TFLite binary with a newer model?
Failed to get registration from op code CONV_2D
AllocateTensors() failed
Requested feature_data_ size 536907080 doesn't match 1960
Feature generation failed
```
