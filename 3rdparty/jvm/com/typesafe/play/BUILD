# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "anorm",
    jars = [
        "//external:jar/com/typesafe/play/anorm_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":anorm_tokenizer",
        "//3rdparty/jvm/com/jsuereth:scala_arm",
        "//3rdparty/jvm/joda_time",
        "//3rdparty/jvm/org/joda:joda_convert",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_parser_combinators",
    ],
)

scala_import(
    name = "anorm_akka",
    jars = [
        "//external:jar/com/typesafe/play/anorm_akka_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":anorm",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "anorm_tokenizer",
    jars = [
        "//external:jar/com/typesafe/play/anorm_tokenizer_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang:scala_reflect",
    ],
)
