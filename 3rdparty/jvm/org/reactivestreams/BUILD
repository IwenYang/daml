# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "reactive_streams",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/org/reactivestreams/reactive_streams",
    ],
)

java_library(
    name = "reactive_streams_examples",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":reactive_streams",
        "//external:jar/org/reactivestreams/reactive_streams_examples",
    ],
)

java_library(
    name = "reactive_streams_tck",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":reactive_streams",
        ":reactive_streams_examples",
        "//3rdparty/jvm/org/testng",
        "//external:jar/org/reactivestreams/reactive_streams_tck",
    ],
)
