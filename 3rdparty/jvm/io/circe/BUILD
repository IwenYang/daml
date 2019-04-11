# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "circe_core",
    jars = [
        "//external:jar/io/circe/circe_core_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":circe_numbers",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/typelevel:cats_core",
    ],
)

scala_import(
    name = "circe_generic",
    jars = [
        "//external:jar/io/circe/circe_generic_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":circe_core",
        "//3rdparty/jvm/com/chuusai:shapeless",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "circe_jawn",
    jars = [
        "//external:jar/io/circe/circe_jawn_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":circe_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/spire_math:jawn_parser",
    ],
)

scala_import(
    name = "circe_numbers",
    jars = [
        "//external:jar/io/circe/circe_numbers_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "circe_parser",
    jars = [
        "//external:jar/io/circe/circe_parser_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":circe_core",
        ":circe_jawn",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
