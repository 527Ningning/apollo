package(default_visibility = ["//visibility:public"])

licenses(["notice"])

cc_library(
    name = "libtorch_gpu",
    includes = [
        ".",
        "torch/csrc/api/include",
    ],
    linkstatic = False,
    linkopts = [
        "-L/usr/local/libtorch_gpu/lib",
        "-lc10",
        "-ltorch",
        "-ltorch_cpu",
        "-ltorch_cuda",
    ],
    deps = [
        "@python3",
    ],
)