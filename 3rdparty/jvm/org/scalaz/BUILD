# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "scalaz_concurrent",
    jars = [
        "//external:jar/org/scalaz/scalaz_concurrent_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":scalaz_core",
        ":scalaz_effect",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "scalaz_core",
    jars = [
        "//external:jar/org/scalaz/scalaz_core_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "scalaz_effect",
    jars = [
        "//external:jar/org/scalaz/scalaz_effect_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":scalaz_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "scalaz_iteratee",
    jars = [
        "//external:jar/org/scalaz/scalaz_iteratee_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":scalaz_core",
        ":scalaz_effect",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "scalaz_scalacheck_binding",
    jars = [
        "//external:jar/org/scalaz/scalaz_scalacheck_binding_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":scalaz_concurrent",
        ":scalaz_core",
        ":scalaz_iteratee",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scalacheck",
    ],
)
