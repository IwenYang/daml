# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "fansi",
    jars = [
        "//external:jar/com/lihaoyi/fansi_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":sourcecode",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "fastparse",
    jars = [
        "//external:jar/com/lihaoyi/fastparse_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":fastparse_utils",
        ":sourcecode",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "fastparse_utils",
    jars = [
        "//external:jar/com/lihaoyi/fastparse_utils_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":sourcecode",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "pprint",
    jars = [
        "//external:jar/com/lihaoyi/pprint_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":fansi",
        ":sourcecode",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "sourcecode",
    jars = [
        "//external:jar/com/lihaoyi/sourcecode_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
