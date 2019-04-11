# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "common",
    jars = [
        "//external:jar/org/scalameta/common_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/com/lihaoyi:sourcecode",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "contrib",
    jars = [
        "//external:jar/org/scalameta/contrib_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":scalameta",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "dialects",
    jars = [
        "//external:jar/org/scalameta/dialects_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "inline",
    jars = [
        "//external:jar/org/scalameta/inline_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":inputs",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "inputs",
    jars = [
        "//external:jar/org/scalameta/inputs_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":io",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "io",
    jars = [
        "//external:jar/org/scalameta/io_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "paradise_2_12_6",
    jars = [
        "//external:jar/org/scalameta/paradise_2_12_6",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_compiler",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "parsers",
    jars = [
        "//external:jar/org/scalameta/parsers_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inputs",
        ":tokenizers",
        ":tokens",
        ":trees",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "quasiquotes",
    jars = [
        "//external:jar/org/scalameta/quasiquotes_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inputs",
        ":parsers",
        ":trees",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "scalameta",
    jars = [
        "//external:jar/org/scalameta/scalameta_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inline",
        ":inputs",
        ":io",
        ":parsers",
        ":quasiquotes",
        ":semantic",
        ":tokenizers",
        ":transversers",
        ":trees",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "semantic",
    jars = [
        "//external:jar/org/scalameta/semantic_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":parsers",
        ":trees",
        "//3rdparty/jvm/com/trueaccord/scalapb:scalapb_runtime_2_12",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "tokenizers",
    jars = [
        "//external:jar/org/scalameta/tokenizers_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inputs",
        ":tokens",
        "//3rdparty/jvm/com/lihaoyi:fastparse",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "tokens",
    jars = [
        "//external:jar/org/scalameta/tokens_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inputs",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "transversers",
    jars = [
        "//external:jar/org/scalameta/transversers_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":trees",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "trees",
    jars = [
        "//external:jar/org/scalameta/trees_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":common",
        ":dialects",
        ":inputs",
        ":tokenizers",
        ":tokens",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
