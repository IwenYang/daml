# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "commons_compress",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/apache/commons/commons_compress",
    ],
)

java_library(
    name = "commons_exec",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/apache/commons/commons_exec",
    ],
)

java_library(
    name = "commons_lang3",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/apache/commons/commons_lang3",
    ],
)

java_library(
    name = "commons_math3",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/apache/commons/commons_math3",
    ],
)

java_library(
    name = "commons_text",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":commons_lang3",
        "//external:jar/org/apache/commons/commons_text",
    ],
)
