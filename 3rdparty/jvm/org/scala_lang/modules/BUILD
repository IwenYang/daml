# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "scala_java8_compat",
    jars = [
        "//external:jar/org/scala_lang/modules/scala_java8_compat_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_library(
    name = "scala_parser_combinators",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "@io_bazel_rules_scala_scala_parser_combinators",
    ],
)

scala_import(
    name = "scala_xml",
    jars = [
        "//external:jar/org/scala_lang/modules/scala_xml_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
