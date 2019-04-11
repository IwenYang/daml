# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "opencensus_api",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/io/opencensus/opencensus_api",
    ],
)

java_library(
    name = "opencensus_contrib_grpc_metrics",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":opencensus_api",
        "//external:jar/io/opencensus/opencensus_contrib_grpc_metrics",
    ],
)
