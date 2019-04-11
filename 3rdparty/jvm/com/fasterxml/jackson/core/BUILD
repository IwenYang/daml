# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "jackson_annotations",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/com/fasterxml/jackson/core/jackson_annotations",
    ],
)

java_library(
    name = "jackson_core",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/com/fasterxml/jackson/core/jackson_core",
    ],
)

java_library(
    name = "jackson_databind",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":jackson_annotations",
        ":jackson_core",
        "//external:jar/com/fasterxml/jackson/core/jackson_databind",
    ],
)
