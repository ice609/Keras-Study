# Keras-Study

Introduction


Keras 是一个高级的Python 神经网络框架，其文档详。Keras 已经被添加到TensorFlow 中，成为其默认的框架，为TensorFlow 提供更高级的API。 如果读者不想了解
TensorFlow 的细节，只需要模块化，那么Keras 是一个不错的选择。如 果将TensorFlow 比喻为编程界的Java 或C++，那么Keras 就是编程界的Python。它作为 
TensorFlow 的高层封装，可以与TensorFlow 联合使用，用它很速搭建原型。 另外，Keras 兼容两种后端，即Theano 和TensorFlow，并且其接口形式和Torch 有几分
相像。掌握Keras 可以大幅提升对开发效率和网络结构的理解。 

1、 Keras 的优点 
Keras 是高度封装的，非常适合新手使用，代码更新速度比较很，示例代码也比较多，文 档和我论区也比较完善。最重要的是，Keras 是TensorFlow 官方支持的。当机器
上有可用的GPU 时，代码会自动调用GPU 进行并行计算。 

Keras 官方网站上描述了它的几个优点，具体如下。 

● 模块化：模型的各个部分，如神经层、成本函数、优化器、初始化、激活函数、规范化都是独立的模块，可以组合在一起来创建模型。 

● 极简主义：每个模块都保持简短和简单。 

● 易扩展性：很容易添加新模块，因此Keras 适于做进一步的高级研究。 

● 使用Python 语言：模型用Python 实现，非常易于调试和扩展。 

2、 Keras 的模型 

Keras 的核心数据结构是模型。模型是用来组织网络层的方式。模型有两种，一种叫Sequential 模型，另一种叫Model 模型。Sequential 模型是一系列网络层按顺序构成的栈，是单输入和单输出的，层与层之间只有相邻关系，是最简单的一种模型。Model 模型是用来建立更复杂的模型的。

中文文档：  https://keras-cn.readthedocs.io/en/latest/

https://keras.io/zh/
           
Tensorflow:  https://morvanzhou.github.io/tutorials/machine-learning/tensorflow/
