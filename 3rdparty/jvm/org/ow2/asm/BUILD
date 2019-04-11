# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "asm",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/ow2/asm/asm",
    ],
)

java_library(
    name = "asm_analysis",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":asm_tree",
        "//external:jar/org/ow2/asm/asm_analysis",
    ],
)

java_library(
    name = "asm_commons",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":asm_tree",
        "//external:jar/org/ow2/asm/asm_commons",
    ],
)

java_library(
    name = "asm_tree",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":asm",
        "//external:jar/org/ow2/asm/asm_tree",
    ],
)

java_library(
    name = "asm_util",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":asm_tree",
        "//external:jar/org/ow2/asm/asm_util",
    ],
)
