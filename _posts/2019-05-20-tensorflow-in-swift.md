---
title: Tensorflow in Swift
date: 2019-05-20 00:00:00 Z
permalink: "/tensorflow-swift"
layout: post
excerpt: Tensorflow-Swift
---

### Using Swift on Tensorflow

```
git clone https://github.com/google/swift-jupyter.git
cd swift-jupyter
docker build -f docker/Dockerfile -t swift-jupyter .
docker run -p 8888:8888 -it --cap-add SYS_PTRACE -v ~/swift-notebooks:/notebooks swift-jupyter
```