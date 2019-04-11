# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "hamcrest_all",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/org/hamcrest/hamcrest_all",
    ],
)

java_library(
    name = "hamcrest_core",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/hamcrest/hamcrest_core",
    ],
)

java_library(
    name = "hamcrest_library",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":hamcrest_core",
        "//external:jar/org/hamcrest/hamcrest_library",
    ],
)
