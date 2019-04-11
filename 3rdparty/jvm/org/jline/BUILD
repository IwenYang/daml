# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "jline",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/org/jline/jline",
    ],
)

java_library(
    name = "jline_reader",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":jline_terminal",
        "//external:jar/org/jline/jline_reader",
    ],
)

java_library(
    name = "jline_terminal",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/jline/jline_terminal",
    ],
)
