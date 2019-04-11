# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "config",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/com/typesafe/config",
    ],
)

scala_import(
    name = "ssl_config_core",
    jars = [
        "//external:jar/com/typesafe/ssl_config_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":config",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_parser_combinators",
    ],
)
