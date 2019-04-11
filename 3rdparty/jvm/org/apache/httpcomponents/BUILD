# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "httpclient",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":httpcore",
        "//3rdparty/jvm/commons_codec",
        "//3rdparty/jvm/commons_logging",
        "//external:jar/org/apache/httpcomponents/httpclient",
    ],
)

java_library(
    name = "httpcore",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/apache/httpcomponents/httpcore",
    ],
)
