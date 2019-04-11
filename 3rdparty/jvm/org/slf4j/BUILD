# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "jcl_over_slf4j",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":slf4j_api",
        "//external:jar/org/slf4j/jcl_over_slf4j",
    ],
)

java_library(
    name = "slf4j_api",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/org/slf4j/slf4j_api",
    ],
)

java_library(
    name = "slf4j_ext",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":slf4j_api",
        "//external:jar/org/slf4j/slf4j_ext",
    ],
)

java_library(
    name = "slf4j_simple",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":slf4j_api",
        "//external:jar/org/slf4j/slf4j_simple",
    ],
)
