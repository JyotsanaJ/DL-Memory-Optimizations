# memory-optimizations
In this repo we plan on going through different memory optimization that came over the years to make the models as efficient as they are today

1. Gradient Checkpointing
2. Gradient Accumulation
3. Gradient Clipping
4. Mixed precision Training

    4.a AutoCast

    4.b Autocast with GradScaler

5. Quantization

    5.a Dynamic quantization

    5.b Post Training Static Quantization

    5.c Quantization Aware Training

Also We talk about onnx (Open Neural Network exchange) which helps convert any model to onnx type. This type makes the model accessible by any framework(pytorch, Tensorflow etc) and is not confined to the framework the model was trained in.

Also we talk about onnxruntime used for fast inference, less memory requirement and faster computation.